Distributed Crawler and Search Engine - Java/Storm/Spark/Elastic MapReduce/AWS Services/HTML/JavaScript [Team of 4]
• Used Apache Storm to develop a crawler that distributes the requests across multiple crawling peers in the Mercator-style   
  and downloads documents into S3. Used netty client for making asynchronous calls and speeding up the crawl rate.
• Developed an Indexer that uses Elastic MapReduce to create a lexicon inverted index from the crawled documents for faster   
  information retrieval. The data comprising of 42 million entries was split across nodes and stored in BerkeleyDB.
• Used Apache Spark to run PageRank and perform link analysis.
• Built a multithreaded HTTP server with a web container to render the search page to the clients, with AJAX calls to the  
  server to load dynamic search results that were based on a ranking algorithm, which approximately took 0.5sec to retrieve
  top ten results.
• Provided support for geo-specific searches, text to speech synthesis and integrated with Twitter and eBay APIs.


Note : Please reach out to me for the source code. 
