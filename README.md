# FOIA-automation-response-analysis

Since Polish authorities do not run a centralized database to collect reports about abuse cases in foster families, for this project, we had to gather data manually from each of the 314 counties in Poland.

Using YAMM email merge, I automated the sending of 318 FOIAs to institutions across the country supervising foster families in regions, 56 regional and district prosecutors' offices, and 17 provincial offices. Each unit replied to us in PDF.

I OCRed the PDFs and conducted text regex to extract the relevant information. Then I used an LLM (GPT-4) to clean up the text. Then, I ran the LLM again to extract the number of cases and their outcomes (investigation discontinued, sentence, etc.).

The story was published at Frontstory.pl: https://frontstory.pl/piecza-rodzina-zastepcza-przemoc-molestowanie-przepisy/
