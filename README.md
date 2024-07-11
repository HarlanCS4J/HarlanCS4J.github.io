![Logo for GenCyber](https://media.defense.gov/2019/Jul/22/2002159967/1088/820/0/190722-D-IM742-2001.JPG)
# Does Your App NEED a Location Sensor?

## Lesson Description: 
This lesson will be an evaluative “tour of features” lesson for app development. Students will learn to be thoughtful about which features are added to their app by investigating the potential for data breaches inherent in adding a feature to your app. 

## Prerequisite Knowledge: 
Students should know the overall organization of the app development environment (Where the tool-trays are located), and how to add items to an app.

Students should have seen and installed apps on devices before.

## Length of Completion: 
This lesson will represent a 20-minute huddle during the planning stages of their final 
group projects. -or-

This lesson will take 1 class period, including presentations.

## Level of Instruction: 
This lesson is aimed at (middle- or) high-school students.

## Applicable First Principles &/or Concepts:  
### GenCyber First Principles
Domain Separation	  Abstraction
**Process Isolation	  Data Hiding**
Resource Encapsulation	Layering
Modularity	Simplicity
**Least Privilege		Minimization**

### GenCyber Cybersecurity Concepts
Defense in Depth	Availability
**Confidentiality	Think Like an Adversary**
Integrity	Keep it Simple

## Resources that are Needed: 
Each student should have:
* Laptop
* AppInventor account
Accommodations Needed: Students may need to present privately to the instructor in another environment. Students may need adaptive technology for interacting with the computer.
Learning Outcomes

LESSON LEARNING OUTCOMES
Students will be able to critically select features that need to be included in their apps.
Students will be able to consider exploits and vulnerabilities as a component of app design to be weighed against other costs and benefits.

Lesson Details

Interconnection: This lesson can be during the planning phase of the final project, where students are making decisions, or can stand alone.
Assessment: Students will present in groups on the vulnerabilities inherent in the components they have:
added to their final project; during the presentation of their app -or-
been assigned from among potentially exploitable components, including apps they’re familiar with that use that component.

Extension Activities: This lesson will create a vocabulary by which to check in during the remainder of the final project.

Differentiated Learning Opportunities: Students who have completed their presentation early can be prompted to define edge cases where the components are optional.
Students who are struggling should be prompted to think about when they’ve installed apps on their devices. What components do apps request access to? Which components don’t require a request?

Lesson


Lesson 1 Details: 
Warm Up: Introduce the lesson as guidance for planning your final project. “As you’re deciding what you want in your app…”
Look back at the Droid, Where’s My Car app. What potential vulnerabilities are there? What would happen if someone found your backpack? What other data could an app collect that you wouldn’t want someone to be able to find about you?
Lesson:
Divide students into groups to each look into the various components of App Inventor. There are 14 component drawers, so each group will look at 2.
User Interface / Sensors
Layout / Social
Media / Storage
Drawing and Animation / Connectivity
Maps / LEGO MINDSTORMS
Charts / Experimental
Data Science / Extension
For most of the groups, the first drawer is largely display components, vulnerabilities there have to do with “Could someone break into it to show you something?” The second group has places where someone could get your data. 
Take a minute to go through your components. For each component decide:
If the component would be difficult to exploit - Put the component name on a green post-it.
If the component could be exploited, but it would mostly be a nuisance (Think rick-rolling) - Put the component name on an orange post-it and a quick note of how it could be exploited.
If the component feels like a vulnerability - put the component name on a pink post-it, and explain what you see.
Example
Slider
ImageSprite

Could someone make your sprite non-clickable, ruining your game?
LocationSensor

The stored location information could lead someone to you or your possessions.


After you’ve made your post-its, put them on the board under your drawer in the table on the board. https://docs.google.com/presentation/d/1YXTkCGAT8RFSiKmLnyVpAhIlloj-2grmgSJbtV9C6AM/edit?usp=sharing
As you’re moving forward to make your app, keep this in mind that your app can create vulnerabilities for your users, or be vulnerable to being hacked so that it doesn’t work like you want. 
