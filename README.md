## topcoder-dl :bookmark:
###### Downloads all Topcoder data-science tutorials and save as PDF

Inspired from this awesome stuff called [Youtube-dl](https://github.com/rg3/youtube-dl)

### Installation

###### Dependency to be installed manually
[wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf)

##### Build from source
```sh
	git clone "https://github.com/tushar-rishav/topcoder-dl.git"
	cd topcoder-dl
	python setup.py install
```
##### Using pip
```sh
	pip install topcoder-dl
```
###Default config:
	target  : TopcoderPdf

### Usage

##### Fetch single post
To fetch single tutorial, say Binary Search, run this in your shell
```sh

topcoderdl -p https://www.topcoder.com/community/data-science/data-science-tutorials/binary-search/

```
Note: the above command will save the pdf in default directory

##### Fetch all tutorial in your custom directory

```sh
topcoderdl -t my_directory_abs_path

```
Note: If the directory do not exists then topcoder-dl will create a new one else the PDFs will be saved in the exsting directory

##### Get help
```sh
topcoderdl -h
```
##### Example
```sh
topcoderdl -p https://www.topcoder.com/community/data-science/data-science-tutorials/binary-search/ -t BSearch_TopCoder
```
The above command will fetch binary-search tutorial from TopCoder and save its PDF in Bsearch_TopCoder directory


### Contributions
Have an idea to make it better? Go ahead! I will be happy to see a pull request from you! :blush:

### License
![gpl](https://cloud.githubusercontent.com/assets/7397433/9025904/67008062-3936-11e5-8803-e5b164a0dfc0.png)
