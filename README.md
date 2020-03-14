## Introduction
The purpose of this project is to transform interesting data presented in a bar chart into something more interactive while at the same time keeping the main message. The visualization here represent the different stages of post-pregnancy of a mother. To be able to come up with this final result, I combined various sources with the main ones being a tutorial from FlowingData  (the link to the tutorial is: https://flowingdata.com/2016/08/23/make-a-moving-bubbles-chart-to-show-clustering-and-distributions/) and a graph tweeted by Caitlin Huton. I would like to thank both Nathan Yau the founder of Flowingdata for his amazing tutorials, as well as Caitlin Hudon, who I got the inspiration from.

### 1. Dataset
As mentionned above, I first got inspired by Caitlin's tweet (https://twitter.com/beeonaposy/status/1215830967719485441) with the following chart:

![Twitter inspiration](/twitter_inspiration.png)

I thus from the graph, estimated the percentage of time allocated for each activity and was then able to construct the dataset used for the D3 visualization. The data powering the animation in the graph can be found here: https://gist.githubusercontent.com/mohamedkhanafer/c98be5b6981264a6d8054a0ae0436898/raw/e620fb6a09bd9a0e8f501d2de4ba93104622610c/gistfile1.txt. In the script above, I included all the detailed steps undertaken to reach this dataset. I advise to go through the code as it contains much explanations.

### 2. Final result usind D3
The final result is the following:

![D3 visualization](/final_result.gif)

The complete visualization with a better quality can be accessed here: https://blockbuilder.org/mohamedkhanafer/8f66b1ffd960a9ec2b604f87d24bc547.
