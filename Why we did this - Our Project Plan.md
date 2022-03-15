# Why we did this - Our Project Plan


WoC (World of Content) has given us, S3-DB02-1, the mission to create a mini PIM to our liking. We received some general information about WoC and started brainstorming from there.

We chose to focus on competition. This means the following:
p.s.: you can also take a look here at some user stories.

**Starting with the suppliers:**

the supplier (e.g. Sligro) has products that they want to sell. In order to sell to as many suppliers as possible, Sligro puts its products on our platform. There are many retailers on this system. For retailers, this is a great platform with a wide choice of products from different suppliers. This means a lot of competition between different suppliers.

**Retailers:**

The retailer (e.g. Jumbo) is looking for products. On this platform, Jumbo has a choice of different products with different brands, prices and stockpile. Jumbo uses this platform to make good choices between different suppliers.

**Site Admins:**

In addition to these 2 important roles, we naturally have the site owners (e.g. superadmins and more). They can also function as the staff of the PIM system. To give you an example: staff can provide customer support for both customers for problems and questions about the platform. Although this is important, we will focus less on this part.

All customers - suppliers and retailers - must have an account to access the platform's content. When creating an account, they can choose which role they have. If the customer chooses the retailer role, they will have access to all suppliers and retailers on the platform. The suppliers for what they deliver, and the retailers to, for example, look at basic statistics of others. A supplier will also have to be able to view the statistics of other suppliers in order to adjust its own, such as prices and delivery updates.

Next up --> [User stories](https://github.com/RensvGemert/S3-GP/blob/main/user-stories.md).

<br />

## The technical side
An overview of chosen technical components, programming languages and build-tools.

### Java.. Why though?
There were no specific requirements on a programming language set by WoC, so we were free to chose our own.
We chose Java as we wanted to learn a new programming language. We mainly used C# in our previous year and as Java has a logical affiliation with C#, we started to look more into it.
Today, Java is one of the most popular programming languages. It powers enterprise web apps, big data pipelines, mobile apps on android and more. Java has a "write once, run everywhere" flexibility that is far more beneficial than one might expect. Instead of compiling to machine-code, like C or C++, it compiles to byte-code, that can run on any operating system without recompiling. Java uses a Java Virtual Machine (JVM) to execute and the machine in question just needs the Java Runtime Environment (JRE) installed.

As Java is so widely used, support for this programming language is not hard to find. Furthermore, Starting with Java, a project can be easily converted to Kotlin.

As almost all our group members plan on using Java in their individual project, it can help in troubleshooting both sides and enhance our productivity.

### Maven vs Gradle
What tool is better suited for our project according to our needs? According to javaatpoint.com, Gradle as well as maven are both considered standard and widely used amongst developers. While Gradle is a popular build tool for Java, Maven is an older and generally used alternative, but can work better with other frameworks such as spring or hibernate. Some key differences between the two are listed below:

### Gradle	Maven
It is a build automation system that uses a Groovy-based DSL (domain-specific language )	It is a software project management system that is primarily used for java projects.
It does not use an XML file for declaring the project configuration.	It uses an XML file for declaring the project, its dependencies, the build order, and its required plugin.
It is based on a graph of task dependencies that do the work.	It is based on the phases of the fixed and linear model.
In Gradle, the main goal is to add functionality to the project.	In maven, the main goal is related to the project phase.
It avoids the work by tracking input and output tasks and only runs the tasks that have been changed. Therefore it gives a faster performance.	It does not use the build cache; thus, its build time is slower than Gradle.
Gradle is highly customizable; it provides a wide range of IDE support custom builds.	Maven has a limited number of parameters and requirements, so customization is a bit complicated.
Gradle avoids the compilation of Java.	The compilation is mandatory in Maven.

>💡Gradle is built to overcome the drawbacks of Maven.

While Maven has benefits on it's own, like enhanced dependency management, a straightforward debugging process, better co-operation among the source code, plugin, libraries and the IDE and reduction of duplication within the project and there is no need to store the binary libraries (third party) within the source control, but it has it's shortcomings, as it is not the newest tool in the shed.

Gradle's benefits include writing a build script with Java programming language, the support of dependency management, high performance in scalable builds, an easier integration process, multi-project structure support, easier migration from other build tools to Gradle and it is easier to maintain.

Our choice for this project: Maven

### React
Credits to Fireship:
[![react in 100 seconds](https://user-images.githubusercontent.com/45943209/158355496-716673dd-4cc7-404f-9823-45c9f8b71d02.png)](https://youtu.be/Tn6-PIqc4UM)



The reason we chose React is due to it's logical building process and it's simplicity. The use of JSX, which allows us to combine JavaScript with html markup, makes the building of a component - which is basically just a JS function - a piece of 🍰.
The changing of values within React makes it easy to debug outcomes and data within the UI.
Furthermore, React has a massive ecosystem, which consists of open-source components from the community for every situation possible.

