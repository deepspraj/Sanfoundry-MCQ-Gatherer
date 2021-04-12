# Sanfoundry-MCQ-Gatherer

A python script which collects all the mcq's from sanfoundry of particular topic (given link).

The script needs to be executed from command line interface else it won't work. (Reason: It require's argument to be passed from command line interface only.)


## Running Locally

Make sure you have [Python](https://www.python.org/) installed.

```sh

git clone https://github.com/deepspraj/Sanfoundry-MCQ-Gatherer.git # or clone your own fork
cd Sanfoundry-MCQ-Gatherer
pip install -r requirements.txt
python mcq_grabber.py --link={url}
```

Your mcq_grabber.py should now run and save .txt file at Sanfoundry-MCQ-Gatherer.

## Link

The script support's all the links on [https://www.sanfoundry.com/](https://www.sanfoundry.com/) except the test and book links.

### Get a desired link

Visit [https://www.sanfoundry.com/](https://www.sanfoundry.com/) and look for any topic which on launch will have same layout (website layout) as this [link](https://www.sanfoundry.com/1000-basic-electrical-engineering-questions-answers/). Then just copy url and paste above as stated.


**NOTE: Don't use curly braces along with the link while pasting.**