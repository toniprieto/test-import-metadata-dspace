# test-import-metadata-dspace

This repository includes some randomly generated csv to test DSpace metadata-import utility.

The collection handle column can be changed with this command (for exemple, for collection 123456789/1234):

	sed 's/123456789\/24/123456789\/1234/' < metadata-import-test-1000-new.csv > metadata-import-test-1000-newV2.csv 
