# [In-Development] Amalgamation: Algorithm Analysis Engine
## An Analysis and Visualisation Engine developed in Java using SWING and the JFreeChart Library. 

Amalgamation is a project I have been developing as part of my current research into algorithms and their applications. My peaked interest rendered me curious and challenged me to develop a novel piece of software to allow the user to run different algorithms and compare the data both, visually in the form of a chart, and analytically in the form of a dataset. 

### How does the concept work:

When a user executes Amalgamation, they will be allowed to select which algorithms they wish to run. In the current development build, Amalgamation supports 10 algorithms however, more will be added as development progresses.

Once the user has selected which algorithms they wish to operate, the user will also choose how many elements they wish the algorithm to sort. To ensure a fair and even dataset, I have limited element values to randomly generate Integers between 1 and 255.

Once all configurations have been set, the user can hit play, this will activate all the selected algorithms to sort a randomly generated array based on the user element specification. Once each array has completed their sort, their performances will be catagorised within an XYPlot Chart and a Table. 

### Here is a preview of a former prototype.
This prototype is different from the current iterations due to the limated user interaction. In this build, the user was not able to specify which algorithm they wanted to run, they must run all algorithms.

![Preview of a former version of Amalgamation](https://media.discordapp.net/attachments/334011383140188161/385694091750408202/unknown.png?width=720&height=397)

### Development thus far:
In the preview image above, the iteration used in that showcase has multiple flaws which have since been dealt with, because of the former engines requirement to run all algorithms at once, memory became quite an issue, 10 sorting algorithms processing 100000 element arays each causes testing computers and laptops to utilise 6GB of Random Access Memory minimum. This will still be an issue if the user decides to run all algorithms at once however, most of the sorting algorithms are fairly fast due to their O(n log n) complexities.

Here is a preview of my current developmental processes, using Trello to keep track of development.

![Preview of Development](https://cdn.discordapp.com/attachments/334011383140188161/385696791376691200/unknown.png);
