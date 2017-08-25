# UDACITY FULL STACK INTERVIEW QUESTIONS
```
About the Job
Objective:  This position involves custom web development. Candidate should be capable of basic application architecture, design input, site layout/user interface, database design/programming, and development.  The right individual for this role will be a motivated and energetic developer who takes initiative, enjoys finding solutions to a varying number of challenges, is detail-oriented, and takes extreme pride in their work.

Primary Job Tasks and Responsibilities:
Create site layout/user interface from design concepts by using standard HTML/CSS practices
Perform routine maintenance of existing sites and applications as needed
In conjunction with existing project management staff – define project scope, goals and deliverables while communicating project status and deliverables with managers and clients
Manage multiple projects simultaneously with excellence while maximizing efficiency, execution, and profitability
Proactively audit existing client websites as well as prospects from a strategic standpoint to make recommendations for improvements and generate revenue

Key Competencies:
Direct work experience using and customizing WordPress
2+ years of rapid web development, using PHP, HTML, JavaScript, CSS and ASP.Net
Direct work experience in SEO with knowledge of tools and techniques
Well versed in different computer applications that are required in website designing and development such as Photoshop, Illustrator, Dreamweaver, etc.
Candidates should have proven programming experience as well as a solid understanding of Object Oriented Design and Programming.
Understanding of web application development processes, from the layout/user interface to relational database structures.
Understand the benefits of SEO and the development skills to support SEO
Critical thinking and problem solving skills

Personal Requirements:
·         Strong oral and written communication skills
·         Ability to communicate directly with peers, managers, and clients while leading development to a completed and successful solution
·         Strong organization skills to manage multiple projects and complete tasks quickly within the constraints of clients' timelines and budgets
·         Ability to grow professionally in a highly flexible and fast-moving environment
·         Awareness and pride in 100% client satisfaction
```

## Question 1
The most influential book I’ve read regarding web development is on Javascript & jQuery by Jon Duckett. The book dives into how to use JavaScript to make web pages more interactive, interesting, and usable. In today’s modern programming world, web pages that are interactive and nail the front-end side of the site on the head, are for more interesting and manage to capture the attention of the user in a greater capacity. This book has influenced my progression into programming immensely by giving me elegant structure to study, and encapturing me into the beauty of web development.

## Question 2
I built a web application called MyLift in the hopes of changing how gym-goers approach working out. I am a certified strength and conditioning specialist and certified personal trainer who wanted to create an application to make fitness programming easier for the general public. I overcame great adversity by learning to program in a completely foreign language (Ember.js). By referring to documentation and asking help from my old college roommates, or joining Slack communities, I was able to seek out help to any problems I ran into and accomplished what I had set out to do. I learned a great deal from planning the application, implementing my ideas, and restructuring the application as I came across necessary changes. Taking challenges like this project head on is fun for me because I love problem-solving. I am very proud in the work that I was able to accomplish, and took initiative to try and solve a problem I had encountered numerous times as a personal trainer with this application. With a passion in both web development and fitness, and being detail-oriented, I found it to be exciting and worthwhile.  

## Question 3
```
def unordered_list(strings):
  # creating unordered list tag
  ulst = '<ul>'

  # iterate over strings
  for s in strings:
    ulst += '<li>%s</li>' % s

  ulst += '</ul>'
  return ulst
```
If we are given a list from user input of any strings they wanted, the function should check whether it was given by user input and if the input is in list form.

## Question 4
XSRF or cross-site request forgery occurs when an attacker pretends to be another user in order to gain access during authentication. In order to resolve this problem, we can send a generated state token with the authentication request to be checked when the response is returned.

DDoS attacks occur when the attacker spams the web server with requests until it can’t serve content anymore. Many DDoS attacks are hard to protect against. However, if the server being attacked is of higher caliber, it would take a lot before being flooded with too much to handle.

## Question 5
```
from flask import Flask
app = Flask(__name__)

import json
import random


@app.route('/')
def hello_world():
  return 'Hello World!'

# Route takes the number of sides on the die as a single argument
@app.route('/roll_the_dice/<int:sides>/json')
def roll_the_dice(sides):

  # Assign the result of the die roll
  dice1 = random.randint(1,sides)
  dice2 = random.randint(1,sides)

  # Return the results of the dice rolled as a json string
  return json.dumps({'dice1': dice1, 'dice2': dice2}, sort_keys=True)

if __name__ == '__main__':
  app.debug = True
  app.run()
```
The route added includes functionality to roll the two dice and return the end result as a json string using json.dumps(). Each roll of the dice is assigned to one of the two dice.

## Question 6
In a year from now, I will have finished a couple more Nanodegrees through Udacity in the subjects of ReactJS and Swift, as well as learning more about Ember. I have found that ReactJS and Ember are similar in a sense, but have some major differences. Some frameworks fit some situations better than the others, and it's best to have a good idea of when to use either one. React's basic concepts are very simple to learn and would be easy to use for small proofs of concept and seems to scale well. Ember is easy to start a new project, but also has a larger learning curve. The web server reloads the page on changes and seems like one of the best frameworks to use on a project to scale well for more complex projects with many different developers. Being informed has proven to be the most helpful in my development journey. However, along with web development, I want to expand my skills as a software developer into mobile development. Much of what I read on the direction of software development has influenced me to pursue ReactJS due to its support of native UI components on iOS and Android.

I never want to stay stagnant in my career. Every single day I will be working to become a better programmer. Eventually, I would like to be in a leadership role that would allow me to share my knowledge with someone who started out where I did. With all that I have learned and continue to learn, I will use my skills to create exceptional websites and web applications that the company I work for can take pride in.
