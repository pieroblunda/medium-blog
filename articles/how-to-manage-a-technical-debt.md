# How to manage a technical debt

Piero Blunda | 4 min read | [View on medium](https://pieroblunda.medium.com/how-to-manage-a-technical-debt-53af3443b927)

![Cover image](https://miro.medium.com/max/1400/1*ypMosjmXRmArDSNUpqlESw.png)

[Technical debt](https://en.wikipedia.org/wiki/Technical_debt) is major reason of disagreement between Scrum Masters and Developers. Try to ask in your team the next question: "Are technical debt negative for your project?" Most people will answer that zero technical debt is better. So, are they right?

**Scrum Masters focus their effort satisfying the Product Owner** by giving the expected product in a reasonable time, but usually they do not consider in the planning the effort necessary to rework code and they feels they are loosing the control when develop needs to do something outside the planning, like re-work code.

**Programmers feels they are in the software project (instead in a business project) and want to resolve all technical debt as soon they detect it** justifying "is the best option for the project because we are sure we need to rework this code in the future". Programmers let know to the Scrum master and start to explain the problem using technical arguments, and usually convince the him because the conversation is technical oriented and scrum master has limited action in this sense.

This is exactly that agile framework try to tell us in the [fourth agile principle](https://www.smartsheet.com/comprehensive-guide-values-principles-agile-manifesto): Business team and developers team are not aligned. So… How we should to approach the technical debt?

## The cost of a technical debit

The first important thing to know is that **resolving a technical debt is not free**. You must invest time to improve the software quality and other resources are involved like testers and developers. Both are limited. Do not forget the risk involved by the possibility to add new bugs or worse yet, broke something. Claig Larman explain in his [excelent book UML & Patters](https://www.amazon.it/Applying-UML-Patterns-Introduction-Object-Oriented/dp/0582832489/ref=sr_1_1?dchild=1&qid=1594364693&refinements=p_27%3ACraig+Larman%2Cp_n_feature_browse-bin%3A509817031&rnid=509815031&s=books&sr=1-1) that the simplest way to classify issues is "functional issues" and "quality issues". In this sense, an issue classified as "technical debt" is not different that others like "new feature", "bug", or "design". In fact, a technical debt is a [software quality](https://en.wikipedia.org/wiki/List_of_system_quality_attributes) bug related.

In an ideal situation, your backlog list does not have any technical debt to resolve, all of them are new features to add to the project without a due date and John Lennon is still live. The worst possible situation is having a lot of technical debt to solve and many functionalities to add in a short time.

**When the level of technical debt increases, the cost of developing a new feature will grow as well. The more technical debt you have, the less you will pay for quality improvements**. The less technical debt you have, the more expensive increasing the quality further will be and will be cheaper the cost of add a new feature. [Krzysztof Liszewski](https://www.linkedin.com/in/krzysztof-liszewski/) (Agile Coach) explain it very well in his blog.

Notice we are talking about time management, instead of programming. In my opinion, a senior programmer is who know manage this situation and find a great value for money.

## Managing the situation

Start by analyze the context in order to understand the project situation by tracking issues. You should know which your situation is. I like follow [extreme programming](https://www.agilealliance.org/glossary/xp) techniques instead open a new ticket in a software like Jira for agility reasons. A good practice is frequently read your own code. You will discover lot of possible issues.

At the code-review time, avoid fixing all things you not agree, or suggest modify code that are not aligned with the print goal. Istead, add a ToDo comment to remember to fix it in the future. Focus in the part code that absolutely can not be merged to the master brach or causes an unstable software.

![Graph 1](https://cdn-images-1.medium.com/max/1600/1*uaBKa-NhQ3y3c4ytRrLXxw.jpeg)

Quality-Velocity software balanceHaving zero technical debt is so expensive for the customer and the project will be fail because it will be a perfect software that nobody pay for it and so, nobody use it. Having infinite quantity of technical debt is so disgusting for developers and an excelent way to demotivate a team. In addition, the project will be fail because adding a new feature will require so many time and does not allow to the customer to show progress.

To identify the technical debt level of your software, ask your customer about how happy is with the development process velocity. There are not a magic number. Use the Agile framework and work together with your customer.

## Timing and non-stop strategy

It seems that following this method we never will correct issues generated and the list can grow without limit. In fact, this is the biggest fear that programmers have. When is the best moment to fix an issue? You should simply follow the iteration goal. Listen you scrum master and resolve only the task of the iteration in order to be aligned with needs of the project. You can also, fix technical issues while business team is waiting other stakeholders or definition.

## Conclusion

Do not forget why you are in the project. Everyone has a goal as team member in their single role, but… do you remember exactly what is the project goal? Focus in your goal. Speak with your scrum master in order to be aligned. Classify technical debt as quality issues (yes! there are bugs too!). Use timeboxing to control time spent and use time to improve KPI's. Did you define KPI's? You should.

## Reference
[Timeboxing - Agile alliance](https://www.agilealliance.org/glossary/timebox)
[Krzysztof Liszewski - Agile blog](https://4agile.pl/how-to-manage-technical-debt/)
[UML & Patters - Book](https://www.amazon.it/Applying-UML-Patterns-Introduction-Object-Oriented/dp/0582832489/ref=sr_1_1?dchild=1&qid=1594364693&refinements=p_27%3ACraig+Larman%2Cp_n_feature_browse-bin%3A509817031&rnid=509815031&s=books&sr=1-1)
[Technical debt - Wikipedia](https://en.wikipedia.org/wiki/Technical_debt)
[Agile manifesto](https://en.wikipedia.org/wiki/Technical_debt)