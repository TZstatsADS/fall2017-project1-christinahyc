# Are speeches given by presidents become simpler? 
(Following Thought of Fall 2017 Project 1: What did the presidents say at their inauguation?)

![image](figs/imTrump.png)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2017


+ project conductor **Christina Huang**

+ Project summary: After analysis of speeches' sentence length in the class, I was wondering whether there is any more scientific index to measure the complexity of each speech. After going through [wiki](https://en.wikipedia.org/wiki/Flesch–Kincaid_readability_tests) I found out that we can use Fresch-Kincaid Reading Ease Score to make the comparison more translatable. Thus I downloading txt files of addresses from [this site](http://stateoftheunion.onetwothree.net/texts/index.html), since it contains more text than the dataset given in class. I used package [quanteda](https://cran.r-project.org/web/packages/quanteda/vignettes/quickstart.html) to calculate Fresch-Kincaid Reading Ease Score and visualized the result in a interactive graph.

+ WHAT I FOUND: I observed a very obvious trend that complexity of recent speeches is less than that of previous speeches. In other words, speeches become more simple. Is that because of the revolution of technology to spread infomation? Or presidents are targeting to more people including those who cannot get higher education? If given more time, maybe we can connect this find with more social science features.

![image](figs/newplot.png)

+ Something just for fun: I tried to generate sentence that "sounds like" given by Trump. This LSTM text generation model is based on [keras](https://keras.rstudio.com/index.html). Running this script takes TONS of time, so please don't consider that into evaluation of "Reproducibility". After 80 epochs, it will provide some really interesting result (somethins like "i want to be the world"). The training data is from [here](https://github.com/ryanmcdermott/trump-speeches/blob/master/speeches.txt) 

![image](figs/interesting_result.png)

+ Please feel free to contact me through yuchen.huang@columbia.edu

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
