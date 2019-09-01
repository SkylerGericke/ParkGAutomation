# ParkGAutomation
Software Engineering Project FHSU Fall 2019 for Parking Garage Automation using Java

Project Members:

Skyler Gericke / James Choi / Charles Hudson / Nathan Romrell / Dean Spector




Problem diagnosis:
   The average parking garage is operated with no computerized system, or a very primitive system. The system may track how many cars enter and exit the garage to keep track of capacity. This system is flawed when taking the customers time into account. If there are only a few parking spots left customers may spend large amounts of time just driving around trying to find a parking spot. This also creates congestion in the garage during peak parking times. This is only if the parking garage displays if the garage is at capacity or not. Some garages may not display this, and customers will drive around looking for a spot when there are none available. 
   
   Most garages work by giving customers a ticket with their time upon entry. This ticket is usually the only piece of information the customer receives. The customer then either has to figure out how long they have been parked for and calculate their cost or wait until they exit the garage to receive their total. In the both cases this causes more wasted time as customers have to spend time figuring the cost out or have to wait to have their money ready until they find the total cost. This can cause congestion and a backup of cars also trying to leave the garage.
   
   The main problem with the current operation of parking garages is the wasted time and the congestion which causes more wasted time. 




Proposed treatment:

   In the average parking garage, a customer is given a ticket when they enter and then have to find a stop and park. Once a customer is ready to take their car out of the garage, they then pay using the ticket they were given on entry. There are several issues with this style of parking garage: 
        1.The customer does not know the full cost until leaving 
        2.The customer must find a spot to park 
        3.The garage and the customer may be unaware if the garage is full

  To make the best use of the parking garage's space and provide a more streamed lined experience for the users. We plan to create an automated system. This system will use a graphical user interface (GUI) that will show available parking spots able to be use or reserve. The reservations will be by the hour, and the cost will be calculated upfront. This way, the system can not only track the places in use but keep track of the spots that will be in use at a later time. Garages could also adjust pricing based on how desirable a particular stop it.

  The goal is to make parking garages running our system more appealing to potential users. Since customers using our system will be able to plan and park with greater efficiency, making more money for the garage and better use of the space.

  To minimize unfair or unwanted charges for garage customers alerts will be used. Our system will also alert the customer if the time for there rented space nearing completion. The customer can then increase the time rental time for there spot. Our system will also take into account customers who need special parking be that oversize car or accessible parking spaces.

  We will measure the effectiveness of our garage system by two metrics. How long it takes for the average customer to park and more importantly, the income of the garage. The goals of our system are to decrease parking time and increase revenue for the garage.




Plan of work: 

The plan of work will start with determining either a system design, class hierarchy, or specific questions by the customer and write methods to tackle the questions. The system design will focus on how to approach the problems that arise and clarify any assumptions. It is the team’s job to handle the ambiguity of the problem through a systematic approach to answer the questions that will ultimately arise. Some questions that must be answered are: How is the parking lot designed? Is it a building or an open space? How is the parking lot accessed? Is there more than one exit/entrance? What is the capacity of the parking lot (i.e. number of parking spots)? 
No matter what type of parking lot, the focus of the work will be on building some type of website interface for customers that will park their cars in the parking lot, a website or app for the valet to know which spots are open, a database that will store statistics and trends, and possibly an application that will interact with cameras and hardware components of the parking lot. Most likely the work will require expertise in HTML, CSS, and javascript for the website interfaces. Java and python may be needed for the application that will interact with hardware components. MySQL and PHP would be required for the database and back end portion of the project.
James Choi is currently experienced in usage of HTML, CSS, javascript, and Java. He is concurrently taking a class covering MySQL and may be able to assist on the back-end portion.
The team size is 5 and this is adequate to tackle the workload over the course of 3-4 months. The estimate for the preliminary cost would depend on how much manpower hours are contributed towards the software requirements. For example, if the parking lot is primarily automated with a conveyor belt and elevator/lift system with very little human interaction needed, there will be much greater manpower hours to design the software systems to cover all the hardware aspects. There would also entail more of a need for safety for a fully automated parking lot because there must be built in fail safes into the system in case of malfunctions. Based on projected workload of 10 hours per week x 16 weeks in semester x 5 team members = 800 hours invested into project. Give or take some will invest more time than others on the team, the range can be 600-1000 hours invested into the project. This manpower hour figure can be further clarified using some statistical formula to give a more accurate representation further into the semester. Since the team members are not full-fledged entry level workers yet, we may command more of an intern’s average salary of 18 dollars an hour (based off indeed.com figures). Therefore, we arrive at 18 x 800 hours = $14,400. However, the company that we intern at for this project will have to charge a higher multiple of this cost to cover the overhead costs like healthcare, benefits, and workspace, etc. Assuming the team knows what they are doing and not getting in over their heads, it would not be a far stretch to give a premium to their services for the end user of the finished product. Therefore, let us place the preliminary estimate of the costs to be $100,000-$300,000.
Our team will know that we have succeeded in this project if we create value for the customer by coming in under budget and manpower hours consumed. Furthermore, we will know the project is a success if we significantly reduce the ambiguity of the diagnosed problem. This can be accomplished through requirements gathering from structured system design, along with requirements analysis and specifications developed through user stories.
