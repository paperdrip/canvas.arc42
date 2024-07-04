---
title: Architecture Communication Canvas
layout: splash
permalink: /architecture-communication-canvas
header:
  overlay_image: /images/splash/acc-splash.webp
  overlay_filter: rgba(0, 0, 0, 0.6)
excerpt: "**The shortest possible description of your architecture**"
---


## Structure of the Architecture Communication Canvas (ACC)


Click on an element to see a more detailed description, or just scroll down.

<div class="grid-container architecture-communication-canvas">

  <a href="#value" class="part requirement value">
  <div class="flex row space-between">
  <div class="flex column">
    <strong>Value Proposition</strong><br>
     <small>
      What specific problems does this application software aim to solve, and what unique values does it offer?
     </small>
  </div>
  <i class="fa fa-briefcase icon" aria-hidden="true"></i>
  </div>
  </a>


  <a href="#stakeholder" class="part requirement stakeholder">
    <div class="flex row space-between">
      <div class="flex column ">
        <strong>Key Stakeholders</strong><br />
        <small>
          Who has been informed or consulted to endorse the proposed initiative?
        </small>
      </div>
      <i class="fa fa-user-friends icon" aria-hidden="true"></i>
    </div>
  </a>

  
<a href="#context" class="part requirement context">
  <div class="flex row space-between">
    <div class="flex column">
      <strong>Scope of the Proposition</strong><br>
      <small>What are the specific objectives, boundaries, and deliverables associated with this proposition?</small>
  </div>
      <i class="fa fa-link icon" aria-hidden="true"></i>
  </div>
</a>
  

<a href="#quality" class="part requirement quality">
  <div class="flex row space-between">
    <div class="flex column">
      <strong>Major Quality Requirements</strong><br>
      <small>What are the specific criteria that must be met? </small>
    </div>
      <i class="fa fa-certificate icon" aria-hidden="true"></i>
  </div>
</a>
  
  
<a href="#components" class="part solution components">
  <div class="flex row space-between">
    <div class="flex column">
      <strong>Components/Modules</strong><br>
      <small>
        Major building blocks of the system,<br>
        important subsystems, modules, services.
      </small>
    </div>
      <i class="fas fa-shapes icon" aria-hidden="true"></i>
  </div>
</a>  


<a href="#decisions" class="part solution decisions">
  <div class="flex row space-between">
    <div class="flex column">
      <strong>Core Architecture Decisions</strong><br />
      <small>
        What assumptions have been incorporated into architecture decisions? 
      </small>
    </div>
      <i class="fas fa-arrows-alt-v icon" aria-hidden="true"></i>
  </div>
</a>
  
  
<a href="#technology" class="part solution technology">
  <div class="flex row space-between">
    <div class="flex column">
      <strong>Technologies</strong><br>
      <small>
        Important technologies used for development and operation.
      </small>
  </div>
      <i class="fas fa-tools icon" aria-hidden="true"></i>
  </div>
</a>

</div>


<div class="legend">
  <div class="placeholder">
  </div>

  <div class="entries">
    <div class="square green">
    </div>
    <span class="label">
      Goals: What should the system do?
    </span>
    <div class="square blue">
    </div>
    <span class="label">
      Solution: How is it done? How does it work? What are the rationale behind the design decisions?
    </span>
  </div>
</div>


<a id="value"/>
### Value Proposition

A value proposition is a clear statement that explains what is the problem to solve, situation to improve and the specific benefits delivers. It is a promise of value to be delivered and a belief that value will be experienced.

* **Identify Needs**: What is it trying to solve? What benefits could it bring?

<a id="stakeholder"/>
### Key Stakeholder

Who has been informed or consulted to endorse the proposed initiative?

* **Not only the architects**: Who are our most important contributors or subject matter experts?

<a id="context"/>
### Scope of the Proposition

What aims to achieve (objectives), the limits or scope within which it operates (boundaries), and the tangible outcomes or results expected from it (deliverables). This inquiry helps clarify the purpose and expectations of the proposition.

* **Make it Clear**: What is the definition in business terms?
* **What it is Not**: What would be out of scope?

<a id="quality"/>
### Major Quality Requirements

Define and rank the three most important quality goals and requirements in order to establish a robust architecture and selecting the right technology. This is essential to ensure these goals meet stakeholder expectations and are achieved successfully.

* **Measurable**: The goal must be able to be measured which ensure it meets the desired standards of quality and performance. 

Include the following but not limited to,

* Uptime Availability
* Security / Compliance
* Accuracy
* Consistency
* Response Time
* Throughput
* Timeliness
* Latency


<a id="decisions"/>
### Core Architecture Decisions

What are the core architecture decision made and the reason leading to it?

* **Assumption**: Are there decision made based on some assumptions? What are those?
* **Rationale and Options Considered**: What are the possible options and what leads to the decision?
* **Following the ASW Architecture Principles**: Architecture fulfills the architecture principles. Are there any one of them that   

<a id="technology"/>
### Technologies

What are the most important technologies used for development and operation of the system?

* **Reuse**: Can existing technology be used, if yes which one.
* **Future Ready**: Are strategic technology such as Generative AI considered?
* **New Technology**: If new technology needs to be used, describe and explain

For example:
* programming languages and technologies
* frameworks (like SpringBoot, .NET, Flask, Django)
* database or middleware
* technical infrastructure like physical hardware, server, datacenter, cloud provider, hyperscaler or similer
* operating technologies and environment
* monitoring and administration technologies and environment  


<a id="components"/>
### Components / Modules

What are the major building blocks of the system
(e.g. modules, subsystems, packages, components, services)?

Which external systems, interfaces or neighbouring systems are depending on?



