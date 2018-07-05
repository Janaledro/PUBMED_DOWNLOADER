Modules description

001_index_download:
This module downloads html data from Pubmed ids.

002_metadata_download:
This mk downloads, fom the results of the first module, the metadata (title of paper, authors, and body of the text).

003a_pdf_download:
Download module which use wget and Firefox browser for the download of scientific papers registered in Pubmed Central (PMC).


003b_snps_finder_from_pdf:
This module convert all the pdfs into plain text and finds SNPs ids (rs) using grep.

config.mk:
Necessary URLs.
# PUBMED_DOWNLOADER
