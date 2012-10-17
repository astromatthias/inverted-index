Inverted Index
---------------

Map Reduce Job zu create an inverted index from text corpora

Create jar with mvn package

Run hadoop local: 

hadoop jar inverted-index-1.0-SNAPSHOT.jar org.fiz.hadoop.InvertedIndex 
			-Dmapred.job.tracker=local 
			-Dfs.default.name=file:/// 
			<local input dir> 
			<local output dir>
