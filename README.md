# CuentasYa

**🌐 Languages / Idiomas:** [English](README.md) | [Español](README_ES.md)

This repository contains all the user experience process behind the app 'CuentasYa', focused on the payment of bills for older adults. 

<img src="Documents/CuentasYa.jpg" alt="CuentasYa" style="width: 200px; height: auto;">

--- 
### Index 

1. [Introduction](#1-introduction)
   - [1.1 Problem Statement](#11-problem-statement)
   - [1.2 Solution](#12-solution)
   - [1.3 Changes](#13-changes)
2. [Team and Roles](#2-team-and-roles)
3. [UX Design Process](#3-ux-design-process)
   - [3.1 Strategy Plane](#31-strategy-plane)
      - [3.1.1 Value Proposition Canvas](#311-value-proposition-canvas)
      - [3.1.2 Canvas Persona](#312-canvas-persona)
   - [3.2 Scope Plane](#32-scope-plane)
      - [3.2.1 Benchmark](#321-benchmark)
      - [3.2.2 Customer Journey Map](#322-customer-journey-map)
   - [3.3 Structure Plane](#33-structure-plane)
      - [3.3.1 Sitemap](#331-sitemap)
   - [3.4 Skeleton Plane](#34-skeleton-plane)
      - [3.4.1 Wireframes](#341-wireframes)
   - [3.5 Surface Plane](#35-surface-plane)
      - [3.5.1 Mockups](#351-mockups)
      - [3.5.2 Explanation](#352-explanation)
4. [Heuristic Evaluation Results](#4-heuristic-evaluation-results)
5. [Accessibility]()
5. [References](#5-references)

--- 
### 1. Introduction 

##### 1.1 Problem Statement

In the modern world, the bill payment process has changed compared to previous years, where was necessary to go physically to the banks, regardless the size of the affair. 

Currently, we harness the advantages brought by the digitalized world, specifically, the ability to put in a single application all the capabilities that a few years ago, would be necessary to attend physically in a bank.

In this context, even with this new facilities, there are still people who avoid this solutions, whether by difficulties with technology or simply tradition, something totally normal considering how recently this new technology has emerged. Whatever the case may be, we can recognize the big problem of the lack of solutions focused on this segment of people, the older adults.

##### 1.2 Solution  

With our project, named 'CuentasYa' inspired by the issue found, we aim to build a solution focused on our senior citizens, a platform where they can centralized all their bills and cards, avoiding the need to travel physically to the banks. 

The platform will be able to indicate inside the app and with notifications and alarms, all the unpaid bills. Furthermore, the main feature is the payment of bills, whether it is full digital or generating a centralized ticket that can be used in the bank. 

##### 1.3 Changes 

Based on the feedback given by other groups, professor and teaching assistants, the changes made to this new version of the project are:
* Add solutions to the observations given by other teams after the first presentation.
* Update the [Sitemap](#331-sitemap) with all the current flows of the application.
* Add final [Mockups](./Documents/Mockups/Images/).
* Add an [Explanation for the Mockups](#351-mockups-explanation), grouping them into functionalities to understand the flow off the application and how these work together.
* Add [Heuristic Evaluation Results](#4-heuristic-evaluation-results) made by another group with an explanation of how these were resolved.

---
### 2. Team and Roles

The team is composed by 5 members, each one with a specific role in the project.
| Name             | Role                      | Description                                                                 |
|------------------|---------------------------|-----------------------------------------------------------------------------|
| Joaquín Faúndez  | Project Manager           | Responsible for the overall project management and coordination.                        | 
| Sebastián Llanos | Analyst                   | Responsible for analyzing user requirements, evaluating data, and translating business needs into technical specifications. |
| Javier Alcalde   | UX Designer               | Responsible for creating user interfaces, user flows, and ensuring a positive user experience throughout the application. |
| Diego Labrín     | Supporter                 | Responsible for providing technical assistance, troubleshooting issues, and supporting the team with various project tasks. |
| Jesús Tapia      | Presenter                 | Responsible for presenting the project and communicating its value to stakeholders. |

---
### 3. UX Design Process

##### 3.1. Strategy Plane

_"Together, product objectives and user needs form the strategy plane, the foundation for every decision in our process as we design the user experience."_ (Garrett, 2011)

###### 3.1.1 Value Proposition Canvas
In our context, to understand what we want to achieve with this application, and what of users want and expect of our app, we used the tools named as **Value Proposition Canvas** and **Persona Canvas**.

> The **Value Proposition Canvas** was a framework to ensure that there is a fit between the product and market. It is a detailed tool for modeling the relationship between two parts: customer segments and value propositions. (B2B International, 2025)

![Value Proposition Canvas](Documents/Value%20Proposition%20Canvas.png)

###### 3.1.2 Canvas Persona
Additionally, to understand who are our segment of users, we used the tool named as **Persona Canvas**, to understand who are the persons to which the application is intended.

> The **Persona Canvas** is a tool that allow collect data about our users segment, making this group of fragmented data, a character that represent the needs of a segment group, generating that users be more real and not unknown.

![Persona 1](Documents/Personas/UX-Persona-Juan.png)
![Persona 2](Documents/Personas/UX-Persona-Tereza.png)
![Persona 3](Documents/Personas/UX-Persona-Carmen.png)

##### 3.2. Scope Plane

_"Strategy becomes scope when you translate user needs and product objectives into specific requirements for what content and functionality the product will offer to users."_ (Garrett, 2011)

In the scope plane, to understand what we are building, we study the competitors present in the market, identifying their best features and what makes them good, and their worst features to not replicate them.

###### 3.2.1 Benchmark
To do this, based in the information collected in the **strategy plane**, we develop a benchmarking that compare the most famous competitors and their functionalities, selecting the best functionalities that can match with the problems that we try to solve, adding others that can work and help in our domain problem.

> Benchmarking is defined as the process of measuring products, services, and processes against those of organizations known to be leaders in one or more aspects of their operations. (American Society for Quality, n.d.)

![Benchmark general](Documents/Benchmark/Benchmarking.png)

For more detailed information about the benchmarking analysis and competitor comparison, please visit the [Benchmark folder](Documents/Benchmark) in this repository.

###### 3.2.2 Customer Journey Map 
Materialized the **Persona Canvas**, and defined the functionalities of the project, we mix this two tools to built a **Customer Journey Map**, a tool that let us understand how our users are going to feel using the system, given the interaction between user and app.

> A **Customer Journey Map** is a visual representation of every experience that a customer has with a brand, product or service. Ideally, a customer journey map captures the customer experience from the consumer perspective, visualizing the touchpoints, emotions and potential pain points they encounter during their relationship with a brand. (Hayes & Downie, 2024)

![CJM](Documents/CJM.jpg)

##### 3.3. Structure Plane 

_"The requirements, however, don’t describe how the pieces fit together to form a cohesive whole. This is the next level up from scope: developing a conceptual structure for the site."_ (Garrett, 2011)

###### 3.3.1 Sitemap
In the context of our application, we used the tool known as a Sitemap, to understand the logical flow of the system through the functionalities that the system will respond to each user interaction. 

> A sitemap is a file that shows the structure of your website, including its pages and content. And the relationships between them. (Pavlik, 2024)

![Sitemap](Documents/Sitemaps/Sitemap-EN.jpeg)

##### 3.4. Skeleton Plane 

_"Defines what form that functionality will take. In addition to addressing more concrete issues of presentation, the skeleton plane deals with matters that involve a more refined level of detail"_ (Garrett, 2011)

###### 3.4.1 Wireframes 
In our applications, based on the functionalities defined in the **Sitemap**, we create views for the application using wireframes.

> A **wireframe** is a top-level blueprint that illustrates the structure of your website, app, or project. It doesn’t include any designs or a great deal of detail. It simply maps the structure and the key elements. (Miro, 2025).

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="Documents/Wireframes/wireframe-01.jpg" alt="Wireframe 1" style="width: 22%; height: auto;">
   <img src="Documents/Wireframes/wireframe-08.jpg" alt="Wireframe 2" style="width: 22%; height: auto;">
   <img src="Documents/Wireframes/wireframe-09.jpg" alt="Wireframe 3" style="width: 22%; height: auto;">
   <img src="Documents/Wireframes/wireframe-22.jpg" alt="Wireframe 4" style="width: 22%; height: auto;">
</div>

To see all the wireframes, due to the high number of images, go directly to the [Wireframes Lo-Fi folder](/Documents/Wireframes).

##### 3.5. Surface Plane

_"The surface plane is the most visible part of the user experience. It’s what users see and interact with. The surface plane is where the visual design comes into play."_ (Garrett, 2011)

###### 3.5.1 Mockups 
To see all the images of the mockups, due to the high number of images, go directly to the [Hi-fi Wireframes (Mockups folder)](Documents/Mockups) or to the [figma link](https://www.figma.com/design/TZPs4cJEpcQoUkov2iKeuV/Cuentas-YA?node-id=178-308&t=HpcX7A2NsWgQR3cF-1).

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
  <img src="./Documents/Mockups/Images/CuentasYA-20.png" alt="Wireframe 1" style="width: 75%; height: auto;">
  <img src="./Documents/Mockups/Images/CuentasYA-23.png" alt="Wireframe 1" style="width: 22%; height: auto;">
  <img src="./Documents/Mockups/Images/CuentasYA-32.png" alt="Wireframe 1" style="width: 22%; height: auto;">
</div>

###### 3.5.2 Explanation 
If you want an explanation about the mockups grouped by their functionalities, go to the next [Link](./Documents/Mockups/Explanation-EN/01.Register-Login.md), where you will find the explanation based on the application flow.

--- 
### 4. Heuristic Evaluation Results 

Considering the heuristic evaluation made by another team, the 'CuentasYa' team used the problems found by this external team to strengthen the application.

##### 4.1 Problems

* In the main dashboard, the section «State of Services» is not intuitive, services unpaid show values, while paid services appear crossed out, which can be confusing.
* The summary screen should include a pay button, to allow the users to pay their debt using the app digital wallet or another method.
* Confusing UI in the scan functionality, because the view suggests the bill must fit exactly, which may generate errors.
* It is unclear how to add money to the wallet, because only allow to add cards.
* The UI doesn't specify how bills are displayed, causing confusion about whether they are current charges or previously added services.

##### 4.2 Solution 

* Now, the states of the services in the upper right corner and the color of the price shown a determined color for each state:
  * Red for unpaid bills 
  * Yellow for pending bills 
  * Green for paid bills

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="./Documents/Mockups/Images/CuentasYA-20.png" alt="Wireframe 1" style="width: 75%; height: auto;">
</div>

* Now, the application shows the summary view with a button to go next to the view, where the app asks the user if this want to pay immediately or do it later.

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="./Documents/Mockups/Images/CuentasYA-30.png" alt="Wireframe 1" style="width: 22%; height: auto;">
   <img src="./Documents/Mockups/Images/CuentasYA-31.png" alt="Wireframe 0" style="width: 22%; height: auto;">
</div>

* Now, the scan doesn't show limiters on the screen, leverage the capabilities of the AI to analyze the image.

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="./Documents/Mockups/Images/CuentasYA-24.png" alt="Wireframe 1" style="width: 22%; height: auto;">
</div>

* Now, in the main dashboard is a big button that allows the user add money to the digital wallet. Additionally, the digital wallet has another view to add money.

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="./Documents/Mockups/Images/CuentasYA-10.png" alt="Wireframe 1" style="width: 22%; height: auto;">
   <img src="./Documents/Mockups/Images/CuentasYA-11.png" alt="Wireframe 0" style="width: 22%; height: auto;">
   <img src="./Documents/Mockups/Images/CuentasYA-12.png" alt="Wireframe 0" style="width: 22%; height: auto;">
</div>
 
---
### 5. Accessibility
Considering the accessibility, in the UX context, as the design and development of software usable for everyone, including those with disabilities such as visual or motor skills, since the entire CuentasYa project has as the main focus older adults, a group that in 2024 reaches 14% of the total population in Chile (Instituto Nacional de Estadísticas, 2025), and have in 2020 a 38.3% of functional dependency due to chronic diseases (Leiva et al., 2020), makes accessibility a pillar of the project, where the usability increases.

The 'CuentasYa' application it's designed to be simple, but aesthetic, so that every user can use the app without effort, eliminating any hard search by the user by not having interfaces overload with details, adding value to the application by not present unnecessary complexity.

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
  <img src="./Documents/Mockups/Images/CuentasYA-08.png" alt="Wireframe 1" style="width: 22%; height: auto;">
  <img src="./Documents/Mockups/Images/CuentasYA-10.png" alt="Wireframe 1" style="width: 22%; height: auto;">
  <img src="./Documents/Mockups/Images/CuentasYA-32.png" alt="Wireframe 1" style="width: 22%; height: auto;">
  <img src="./Documents/Mockups/Images/CuentasYA-36.png" alt="Wireframe 0" style="width: 22%; height: auto;">
</div>

As a main functionality, the 'CuentasYa' application has an intelligent agent to help the user to resolve their questions and concerns, which is built in a way that works like a natural conversation where the agent understand the context of the person via the data obtained through the chat, to help the user until he is satisfied.

<div style="display: flex; gap: 10px; justify-content: center; align-items: center; flex-wrap: wrap;">
   <img src="./Documents/Mockups/Images/CuentasYA-21.png" alt="Wireframe 1" style="width: 22%; height: auto;">
   <img src="./Documents/Mockups/Images/CuentasYA-22.png" alt="Wireframe 0" style="width: 22%; height: auto;">
</div>

---
### 6. References
- Garrett, J. J. (2011). The Elements of User Experience: User-Centered Design for thed Web and Beyond. New Riders.
- B2B International. (2025). Value Proposition Canvas. Retrieved from https://www.b2binternational.com/research/methods/faq/what-is-the-value-proposition-canvas/
- American Society for Quality. (n.d.). Benchmarking. Retrieved from https://asq.org/quality-resources/benchmarking
- Hayes, M., & Downie, A. (2024, October 11). Customer journey map. Retrieved from https://www.ibm.com/think/topics/customer-journey-map
- Pavlik, V., Shirlow, C., & Mustapic, B. (2024). What Is a Sitemap? Website Sitemaps Explained. Semrush Blog. Retrieved from https://www.semrush.com/blog/website-sitemap
- What is a Wireframe & its Role in the Design Process | Miro. (2025, May 25). Retrieved from https://miro.com/wireframe/what-is-a-wireframe
- Figma repository: https://www.figma.com/design/TZPs4cJEpcQoUkov2iKeuV/Cuentas-YA?node-id=178-308&t=HpcX7A2NsWgQR3cF-1 
* Instituto Nacional de Estadísticas. (2025, 27 de marzo). Primeros resultados del Censo 2024: 18 480 432 personas fueron censadas en Chile, manteniéndose la tendencia de envejecimiento de la población. INE. Retrieved from https://www.ine.gob.cl/sala-de-prensa/prensa/general/noticia/2025/03/27/primeros-resultados-del-censo-2024-18.480.432-personas-fueron-censadas-en-chile-manteni%C3%A9ndose-la-tendencia-de-envejecimiento-de-la-poblaci%C3%B3n
* Leiva, A. M., Vásquez, I., González, J., & Muñoz, L. (2020). Personas mayores en Chile: un desafío pendiente. Revista Médica de Chile, 148. Retrieved from https://www.revistamedicadechile.cl/index.php/rmedica/article/view/7695/5978
