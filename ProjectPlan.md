# Repository Plan 

1. Person one, initializes a repository and adds this repository plan. 

--------------------------------------------------------------------------------------------------------- 

2. Person one, creates a branch called TaskEstimation, adds a file called TaskEstimation.md, links 5 sources, identifies a common theme, and writes about a personal experience. Then they commit to the branch. 

3. Person two, creates a branch called CodeReviews, adds a file called CodeReviews.md, links 5 sources, identifies a common theme, and writes about a personal experience. Then they commit to the branch. 

4. Person three, researches a topic, creates a branch called "ResearchedTopic”, adds a file called “ResearchedTopic.md, links 5 sources, identifies a common theme, and writes about a personal experience. Then they commit to the branch. 

--------------------------------------------------------------------------------------------------------- 

5. Person one, pulls CodeReviews, identifies a second common theme, and writes about a personal experience. Then they commit and create a pull request. 

6. Person two, pulls "ResearchedTopic”, identifies a second common theme, and writes about a personal experience. Then they commit and create a pull request. 

7. Person three, pulls TaskEstimation, identifies a second common theme, and writes about a personal experience. Then they commit and create a pull request. 

--------------------------------------------------------------------------------------------------------- 

8. Person one, reviews the pull request for “ResearchedTopic”, provides feedback and can choose to reject or accept the pull request. If rejected, person two is responsible to make corrections. Repeat step until accepted. 

9. Person two, reviews the pull request for TaskEstimation, provides feedback and can choose to reject or accept the pull request. If rejected, person three is responsible to make corrections. Repeat step until accepted. 

10. Person three, reviews the pull request for CodeReviews, provides feedback and can choose to reject or accept the pull request. If rejected, person one is responsible to make corrections. Repeat step until accepted. 

--------------------------------------------------------------------------------------------------------- 

11. Person two creates a branch called Introduction and adds a file called introduction.md. They will explains the purpose as well as the structure of the document. It will have a section for each topic that introduces the topic briefly and then summarizes the most important guidelines in bullet points / diagrams. Note that it's just as important to highlight bad practices to avoid as good practices to follow. Each section must also contain links to the reference articles for further reading. They will then commit and create a pull request. 

12. Persons one and three will review the pull request for Introduction, provides feedback and can choose to reject or accept the pull request. If rejected, person two is responsible to make corrections. Repeat step until accepted. 

# Git and Pull Request Rules
1. Make sure to never commit to main. All progress should exist on separate feature branches and then merged into main after. 
2. Branches should adequately describe the work being done on them. Follow the naming format "article-[name of article]". 
3. Work can be committed after a section of work has been completed (e.g. a new paragraph added) however PRs must only be published when the agreed upon work has been completed (e.g. new section added to article).
4. Commit messages should adequately describe the work done as part of that commit.
5. PR titles must accurately reflect the work done as part of the PR.
6. PR descriptions should feature a few lines describing the work done in the PR.
7. PRs cannot be merged until at least 1 other person reviews the PR. When reviewing, check for typos, consistency and cohesiveness and general errors. 

# Project File Structure/Formatting
1. All images should be put in /images and use relative paths
2. Articles should be put in /articles/[name-of-article]
3. Add sources to sources.md file, that exists in the root directory with this project plan. Use a hyperlink to link to the source.
4. When creating a title, use "#"
5. When creating a heading for a section, use "##"
6. When using subheadings, use "###"
7. Bullet points can be done with "*"