# Practice Azure Policy
![AI](img/title.png)

----------------------------------------------------------------
## Process:
##### -We login in [Azure](https://www.portal.azure.com)
##### -Azure Policy allows us to crate rules to manage the cloud.
##### -Create a resource group.
![Policy](img/1-p.png)
##### -Set a name, click on review and create.
![Policy](img/2-p.png)
##### -Now, we look for policy and click on it.
![Policy](img/3-p.png)
##### -We have Events section, where you can see wich rule is met and wich is not.
![Rules](img/4-p.png)
##### -Now, we have Remediations, where we can see the errors and correct them.
![Rules](img/5-p.png)
##### -In definitions section, we have policy definition, and initiative definition, the first is a rule, and the second is a set of rules.
![Rules](img/6-p.png)
#### -We go to create a new rule... click on policy definition.
![Rules](img/7-p.png)
##### -In definition location cliclk on launch scope selector... 
![Rules](img/8-p.png)
##### -Choose your subscription and click on select.
![Rules](img/9-p.png)
##### -Set a name, and you have to describe your rule.
![Rules](img/10-p.png)
##### -Click on save.
![Rules](img/11-p.png)
##### -You can assign the rule.
![Rules](img/12-p.png)
##### -You can select the resource group.
![Rules](img/13-p.png)
##### -Or you can make exceptions.
![Rules](img/14-p.png)
##### -We have to assign policy.
##### -Go to Assignments section.
##### -Click on Assign policy.
![Rules](img/15-p.png)
##### -Click on scope.
##### -Select your resource group.
![Rules](img/16-p.png)
##### -Click on policy definition.
![Rules](img/17-p.png)
##### -Search policy definition, in this case, allowed location, click on it.
![Rules](img/18-p.png)
##### -Select Parameters section, we have to choose the allowed location.
![Rules](img/19-p.png)
##### -Now, you have to select all the allowed locations.
![Rules](img/20-p.png)
![Rules](img/21-p.png)
##### -If you want, you can set a non-compilance message, in the Non-compilance messages section.
![Rules](img/23-p.png)
##### -Then click on review and create.
![Rules](img/22-p.png)
##### -To see if this work, lets to create an App Function.
#### -Search App Function.
![Rules](img/24-p.png)
##### -Click on create.
![Rules](img/25-p.png)
##### -Select a resource group created.
##### -Set a name.
### -Is very important select a regin outside the American Country.
![Rules](img/26-p.png)
##### -Click on review and create.
##### -You should see a error, click on the error.
![Rules](img/27-p.png)
##### -You can see the message..
![Rules](img/28-p.png)
## 🔥🔥Congratulations..! You created an Azure Policy🔥🔥