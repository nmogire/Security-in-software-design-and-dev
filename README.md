# Security-in-software-design-and-dev
A software project plan, under the secure development life cycle (SDLC)

This project is designed to guide the developer through software security design under the secure development life cycle. It is a hands-on research and development exercise focused on security-oriented design and development. The process will follow through several stages of security-oriented development, scoped with primary reference to the microsoft security engineering practices and the secure development life cycle as follows:
1. Project Description and Documentation Plan 
2. Application Requirements
3. Design 
4. Threat Modelling and Tracking
5. Development Plan
6. Implementation
7. Testing
8. Periodic Verification Review
9. Security Evaluation
10. Release Planning and Documentation
11. Software Release

Each step of the project cycle has two key components:
- **The Development**: writing the software
- **The Documentation**: writing notes on the development considerations, tools and processes, and creating a wiki 

If you get through the steps below, you will have an application, its documentation and a wiki.
</br>
✨✨✨</br>


<details><summary>1. Project Description and Documentation Plan</summary>
<p>       
This section is concerned  with the project definition and setup of a documentation plan. It will include the following steps:</br>
           
- Start a file that will be the main documentation of the application. Include a title and an abstract about the application and then add to the document as you continue through the rest of this guide.</br>          
- Make a duplicate of the above file to be the developer documentation of the project which will include more details such as: the low and high fidelity prototyping and results, interesting errors or findings and other developmental details that can be used for reference about the product’s development history.</br>
- Add to the above documents an introduction section and write a brief description of the project by defining the following items:</br>
           - The name and nature of application to be developed e.g. password manager, social media post reviewer..etc</br>
           - Briefly describe the problem the application being developed will be solving</br>
           - Application name</br>
           - Application type e.g. Java Applet, Browser Extension, Web Application, ..etc</br>
           - Development Tools:</br>
                   -- A listing of selected development language, IDE and any other tools whose relevance is known at this stage.</br>
                   -- This list will grow as the documentation continues throughout the development process.</br>
- Setup a source code management and version control repository ( e.g. GitHub or Subversion) for the project and open an issue list for scheduling the development</br>
- Create a Kanban board for managing the development phases </br>
- Create a README document for tracking details of development changes </br>
- Include in the documentations a quicklink to each of the above and any other workspaces as relevant</br>
</p>
</details>

<details><summary>2. Application Requirements </summary>
<p>
           
This section is concerned  with defining the functional and design requirements of the application and what will be necessary in order to meet those items. Add to the documentation an application requirements section to record each of these:
                      
- Define the functional requirements of the program
- Define the design requirements of the program
- Define security requirements of the program
- Define privacy requirements of the program
</p>
</details>

<details><summary>3. Application Design </summary>
<p>
           
This section is concerned  with establishing the application prototype design. Add to the documentation an application design section and document as you go through each of these:
                      
- Microsoft SDL (https://www.microsoft.com/en-us/securityengineering/sdl/practices)
- Outline the design features to implement in order to meet the functional, design, security and privacy requirements defined earlier
- Create a low fidelity paper prototype of the application as in this example, https://www.youtube.com/watch?v=JMjozqJS44M 
User test the paper prototype and record the findings in the developer documentation according to:</br>
           - Ease of use</br>
           - Ease of taking security actions
- Create a high fidelity mockup of the application
- User test the high fidelity prototype and record the findings according to:</br>
           - Ease of use</br>
           - Ease of taking security actions

</p>
</details>

<details><summary>4. Threat Modelling and Tracking</summary>
<p>
           
This section covers threat modelling of the application, which includes scoping, defining and preparing for threat management in the development process. Add to the documentation a threat modelling and tracking section to record each of these:
- Security and Privacy Requirements:</br>
           - Define the security requirements for your program</br>
           - Define the privacy requirements for your program</br>
- Attack Surface Analysis and Quality Gates(or Bug Bars):</br>
           - Determine privilege levels for the application and perform an attack surface analysis</br>
           - Define levels of security for your program E.g. security</br>
           - Define levels of privacy for your program. E.g. privacy</br>
- Threat Modeling: </br>
           - Determine which parts of the program need threat modeling and security reviews</br>
           - Create a graphic representation of all the information in the program and how it is connected e.g. using  a data flow diagram (DFD.</br>
           - Compile a list of potential vulnerabilities based on a similar program, that could apply to this one</br>
           - Add privilege boundaries to the information diagram based on the quality gates and then categorize the possible threats</br>
           - Examples on threat modelling: SDL threat modeling tool, here </br>
- Risk Assessment Plan for Security and Privacy:</br>
           - Determine criteria for assessing and reviewing security of the application</br>
           - Determine criteria for assessing and reviewing security of the application</br>
           - Example: template example
- Security Tracking:</br>
           - Define a plan for keeping track of security flaws that may arise throughout the development process e.g. using the github issues feature
</p>
</details>

<details><summary>5. Development Plan</summary>
<p>
           
This section is concerned with defining the project course more specifically with focus on the tools to be used and the specific components to be developed. Add to the documentation a Development Plan section to record each of these:
- Project tools: </br>
           - Compile a comprehensive list of approved tools for the project. (example). Include tool versions to account for differences between versions e.g. of the same compiler/IDE/etc.</br>
- Deprecated/Unsafe Functions in Project Tools and their alternatives:</br>
           - Identify and list any relevant unsafe or deprecated functions specific to the approved tools. Specify a list of approved alternatives for the project as relevant.</br>
- README Design:</br>
           - List the application components planned for development</br>
           - Specify the tasks involved in development under each component</br>
</p>
</details>

<details><summary>6. Implementation</summary>
<p>
           
This section is concerned  with the application coding and code documentation. Add to the documentation an implementation section for these items:</br>

README:
Under each component planned for development in the README, record what tasks are complete after each work period,</br>
Note what is pending at each working period,</br>
Note what each project participant will be handling next</br>
Code: 
Write the code</br>
Document the code as you go</br>
Add feature documentation to the project manual and the developer manual</br>

</p>
</details>

<details><summary>7. Testing</summary>
<p>
           
This section is concerned  with defining and carrying out various tests to keep the security level of the application under development above defined benchmarks. Add to the documentation a Testing section to record each of these:
Static Analysis:</br>
Choose a static analysis tool to use during the development process. Use this tool each time you recompile the code. Document the tool and analysis outcomes after every few tests. Example: Checkstyle for Java,</br>
 Dynamic Analysis:</br>
Choose a dynamic analysis tool. Document the tool and analysis outcomes after every few tests. Test the code after every significant change to verify that the program is responding as expected.</br>
 Fuzz Testing </br>
Attempt to break or hack into your program using various techniques e.g. focus on the OWASP top 10 vulnerabilities, or run an advanced fuzz test. Document the details of the hacking attempts and the outcomes.</br>

</p>
</details>

<details><summary>8. Periodic Verification Review</summary>
<p>
This section is concerned  with periodic reviewing of the application security using the previously set benchmarks as a project security maintenance effort. </br> This part of the exercise is interleaved with the code development. Periodically add to the documentation testing sections a continuation on each of these:</br>
 Attack Surface Review:</br>
Revisit the attack surface of the application including any changes in the approved tools such as updates, patches..etc or any new vulnerabilities reported. </br>
Similarly conduct a periodic review of the application via static analysis, dynamic analysis and fuzz testing.

</p>
</details>

<details><summary>9. Security Evaluation</summary>
<p>
           
This section is concerned  with conducting a final security review at the end of application development to help determine the security assurance level of the application before release. Add to the documentation a security evaluation section to record each of the final security review:</br>
Use the established threat model benchmarks together with the static analysis, dynamic analysis and fuzz testing to conduct a final review on the code and document the outcomes.</br>
Also run the program as an end user and user test the different features of the program</br>
Grade the program security with a documentation of reasons. Potential security outcomes may include but are not limited to the following examples from the MSDLC FSR Process: Passed FSR, Passed FSR with exceptions, or FSR with escalation. </br>

</p>
</details>

<details><summary>10. Release Planning and Documentation</summary>
<p>
           
This section is concerned  with establishing a response protocol for security and privacy issues that may arise once the application is released, and ensuring documentation is complete and ready for release and archiving as needed. Add to the documentation a release section to record the incident response plan:</br>
Incident Response Plan. Example guides. Specify:</br>
A Privacy Escalation Team which may include roles such as: Escalation manager, Legal representative, public relations representative and the security engineer. </br>
Contact details that users can reach the team at in case need arises. </br>
A standard procedure for incident response. Example.</br>
Review the application manual and developer documentations and revise for release and archiving.</br>

</p>
</details>
<details><summary>11. Software Release</summary>
<p>
           
This section is concerned  with organizing final documentation, licensing and creating a user guide before application release. Add to the documentation a release section to record the following:</br>
Create a release version of the program.
Create a documentation archive. Include:</br>
A summary of features, version number, future development plans</br>
A final README with technical notes on the program e.g. specifications for usage environment, how to install/uninstall the program and links to download pages.</br>
For the developer manual, include closing thoughts on the outcome of the program including developer notes on challenges, surprises, Important achievements disclaimers/caveats etc</br>
Create a Wiki Page for the project. GitHub wiki pages are suggested for this. Include in the wiki a brief user guide and notes on accessibility of the application. Sections may include:</br>
Step-by-step guide of how to use the program (easy to follow and illustrated with annotated screenshots)</br>
Security and privacy notes, terms of use, caveats and disclaimers related to usage of the software</br>
A release license or copyright to the work</br>
Contact information where the security team can be reached e.g. incase bugs are discovered by users.</br>

</p>
</details>
<details><summary>References </summary>
<p>
           
- Microsoft SDL (https://www.microsoft.com/en-us/securityengineering/sdl/practices)
- OWASP top ten proactive controls (https://owasp.org/www-project-proactive-controls/) 
           
</p>
</details>
