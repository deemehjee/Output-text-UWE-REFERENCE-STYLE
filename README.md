# Output-text-UWE-REFERENCE-STYLE
This code defines a function that prompts the user for input to generate Harvard-style references and in-text citations for a given text. The function contains a while loop that continuously prompts the user if they would like to search another database. If the user chooses to search another database, the function prompts the user for input again to generate references for the new text.

The function consists of four main steps:

Scrape data from researches, articles, databases
Apply UWE Harvard style referencing algorithm
Produce the corresponding reference list
Produce the corresponding in-text citations

Within step 1, the code attempts to scrape data from the Google Scholar website using the requests and BeautifulSoup modules. If the results are empty, the user is prompted to enter a custom database URL, and the code attempts to scrape data from the custom URL. If the results are still empty, the user is prompted to try again. Steps 2, 3, and 4 involve parsing the scraped data and generating the corresponding references and in-text citations. The references are sorted alphabetically by author and numbered sequentially, and the in-text citations are numbered sequentially as well.

After the function is defined, the code contains another while loop that prompts the user if they would like to search another database. If the user chooses to search another database, the code prompts the user for input again to generate references for the new text. If the user chooses not to search another database, the program exits.
