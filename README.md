# INTRODUCTION
I started web scraping since 2009 for my PhD research and other works. I experienced nearly all problems and solutions in web scraping, and now want to share the experience by doing a
this school for web scraping. 

People use different terms (e.g. web crawling) but reference to a same thing: I want get some raw data from certain online resources in order to extract for future purpose. The online sources generally refer to either web pages or web API [reference to web api]. The raw data could be in different format types, such as HTML, XML, JSON, text. The raw data need to be extracted to store in a structured format, file or database.

Basically, web scraping technologies mimic how you access a target web source in your familiar ways (e.g. via web browser and mobile phone), but in a automatic fashion. Imaging you want to access your twitter account. you type http://www.twitter.com into the address bar of your web browser and press ENTRE key, the web browser connect and wait for the response from the twitter website. Once responded, your browser will received a HTML file, then automatically process the returned HTML file and rendered into what you can look like. 

In web scraping, you need to do what the browser do and handle the rendering job by yourself. In the same case, you need to develop a program to do these jobs: 1) do hard scraping or API scraping to get web resource from the target website, 2) extract the information from the returned web resource, 3) decide next steps. This school currently does not cover how to future use of the extracted data (may add in future), it only talks about the web scraping. A general web scraping process can be abstracted in this diagram [add the diagram]. 

Although the general principle of web scraping is very straightforward, there are many condition you may not be able to image now. For example, web scraping is a battle between you and the target website, the target may have millions of reason and also technologies to block your scraping. For example, web scraping is not only a technology solution, but also business strategy and ethic issues, you need to be aware of them when you are doing some formal scraping. This school aims to illustrate most of them by giving examples from basic to advance levels. 

The examples given in this school aims to improve fundamental understanding, so will try not to existing scraping tools but develop from scratch. All the codes are written in Python 3.5 so far. You may wish to gain some basic knowledge about Python programming if currently do not have. All the examples try to simulate a real problem you may meet in web scraping. What should I do if the target website in following situations:

1. need a username and password?
2. gives an API?
3. require OAuth?
4. used my daily quotation?
4. block my IP? (think I am a bot?) (Google Play)
5. think I am a bot? use Selenium (Linkedin)
6. use Distill Network (crunchbase.com)
6. extremely restrict and you have tried everything? ()

Last reminder before school open, web scraping can be challenge sometimes and both scraping and anti-scraping technologies are developing so far. So if your problem is too difficult or if your project deadline is too closed, it may save you lots of time and money by contacting or hiring some experienced one like me ^_^. 

## A basic example
We start with a basic example. 

```
def exzp_basic():
    url = 'http://www.google.com'

```

## WHY WEB SCRAPING IS NON STOPPING