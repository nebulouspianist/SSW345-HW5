Design:

1. The most useful design methods are the UML diagrams, like the sequence diagrams and class diagrams. Sequence diagrams really give us a clear thought about how the bot should work in terms of an overall process, and we always know exactly what functions should be included in the bot. Class diagram also gives us an idea of how to implement the bot in code.

2. There wasn’t any extremely difficult part in the design process, but I would say the most difficult part is the overall brainstorming. First of all, it is just hard to get a lot of great ideas in a short period of time, and the user story would be a good example: Our group easily came up with 2 use cases, but when we wanted to get more we found it either too hard to implement or trivial. Also, as we go deeper in brainstorming, it is very likely that we need to adjust our previous design or even create a new one. But I think there is no method to directly improve the experience on this part. If we have more experience, we can get a high quality design at the very beginning of brainstorming and we don’t have to adjust that much later.

3. I will definitely use the sequence diagrams and story boards again in the future. I think it really gives us a clear idea of the requirement of the project, and we can think from the user side instead of just the engineering side. By having a storyboard, our members won’t go too far away from the actual requirements and we can take care of the user experience. For example, in our project, our story board says users enters the method and library he asks for in a command with a prefix and the bot will return the answer. It is very simple but it states the requirements very clear as well. I think it would be helpful in other projects in the future.


Implementation:
1. One of the best things is that our group members have fairly good coding habits. Once we finish implementing a single feature, we want to run tests to make sure there are no bugs, and then we keep implementing the next feature. This makes our group members have pretty good code quality and our code reviewer doesn’ have to do a lot of work. Since our project is rather simple and straightforward, there were not many components, we were basically just using the black box testing method, but it worked quite well. 

2. The most annoying thing is always the debug process. When we were testing the code, it is likely that some special inputs will make the system not running correctly. For example, in our Example Bot, we are trying to look at stack overflow to look for the answer of what user is asking for, when inputs are normal like “get java”(which means users are looking for get() method in java library) it works perfectly, but if the user is asking for method in discord.js, the extra dot will break the url and cause error. There is no way to prepare for this beforehand, and things like this makes the debug process extra hard. I think the only way to make the debug process easier is to get more experience.

3. I will try to keep the good coding habit, which is to test as frequently as possible. Also, I would like to try different testing methods in the future when I am doing more complicated projects, like writing unit test cases for different components of the code. 


Process:
1. A big thank you to github, the branches function is really helpful to us, it perfectly avoids the problem that our code will conflict with each other. What we did was each member has his or her own branch, and we merge our code by sending pull request, and all the code are reviewed by David, who knows most about typescript. It worked very well. The project board in github was also very helpful, we divided the implementation into small and straightforward tasks, and it gives us a very clear idea of what we need to do now. 

2. The process went pretty well overall, so I don’t think there are any special difficulties. One thing I do want to say is that, because I know very little about typescript and node.js, I had to learn from the beginning and pick the relatively easy tasks from the project board. So I think I contributed a little less in terms of implementation. This is also about experience, and I am pretty sure after this project, I can do better in other projects in the future.

3. Github is the best, I will definitely use github in other projects. The branches and pull requests functions are awesome. And assigning one person, maybe the best coder in the team, to be the code reviewer, is very important as well. Too many people having the power to change the main branch will cause a mess, so I think there should be only one person to decide how to merge the code, so the code is consistent. I will do that in future projects as well.


Overall:
	I think design, implementation and process covers different part of a project, so benefits in these three parts are different but they don’t conflict with each other. A good design helps the project as a good organization in ideas and requirements; a good implementation can improve the code quality and easier to read and debug; and a good software process could help make the code consistent and make sure all members can contribute without conflicting with each other. I think all three aspects could help make the project better.
