This was the final project of Duke's CS 290: Educational Technology. I worked with a classmate to create a learning platform for a Visual Media Studies class we both took (Intro to Visual Culture).

# CompSci 290 Final Project - Web part
## Arely Sun

Final demo: https://drive.google.com/file/d/1WSPnmE2sWUgSnqPKqzEwQY19Bv2u-yXO/view?usp=sharing

### Project Goals
My project with Sofa aims to enhance the experience of the Duke VMS202: Intro to Visual Culture course, which we both took in the fall. It includes a study center web app and an AR textbook experience that is accessed through a QR code in the study center.
 * With the goal of engaging students whose primary career interests are not related to arts and whose experience in the field is minimal and making visual culture accessible and engaging to people outside of the university system, we conceptualized the project around the overarching theme of experiencing art rather than memorizing theoretical information about it.
* This project transforms the textbook An Introduction to Visual Culture into an art gallery where the students are transported by means of an AR Snapchat filter. The users are able to see the artworks around them, listen to an audio guide, follow along with the text, and take both written as well as voice notes. The textbook is embedded in a study center that ensures retention of the course’s content, enhancing or replicating the experience of a student taking VMS 202 at Duke. The study center organizes notes a student took in the gallery, provides AI-generated practice problems, and offers students a chance to interact with other students to discuss topics and artworks with the aid of AI—something especially helpful for students taking the class online.

The website is accessed through the HTML file. Clicking on the "doors" on the site leads you to the (dummy) QR code to the AR element, AI discussion tool, AI tutor tool, and notes center (interactive wireframe, not implemented).


### Theory and research
According to a [study](https://link.springer.com/article/10.1007/s40593-016-0107-y) on computer-supported collaborative learning in open online courses, three factors strongly related to student perceptions of online courses: clarity and consistency in course design, contact with / feedback from course instructors, and active discussion. These elements are addressed through the use of AI to guide student learning and provide responses to questions as well as the discuss feature, where students actively discuss topics of their choice with other learners. The discuss feature also relates to connectivism. Duke and non-Duke and combine ideas from different sources and engage in an online learning network, allowing for different perspectives and improved critical thinking skills.


### Justification of features and design
The AI tutor supports the Zone of Proximal Development theory, as the AI is able to give students 24/7 support through answering questions. Again, the discuss feature supports connectivism by establishing a learning network. The discuss feature also promotes inclusivity and accessibility since it allows students outside of a university to have a valuable, engaging learning experience in the humanities. Providing many options for engaging with course content supports UDL; students can support their learning through practicing exam questions, having discussions, or reviewing notes.


### Privacy Policy
Information We Collect
 * We will collect your login information (username, email, password) as well as any personal details listed in your user bio like location, pronouns, and interests.
 * We will collect the information on the ways you interact with the app, specifically, the amount of time spent on each feature, types of questions asked, and topics mentioned in discussions with other users or the AI tutor. None of this information will be attached to your personal account, but will rather be part of a larger anonymised dataset.
 * We will be recording your chat history in the discuss and AI tutor features.

How We Use Your Information
 * We will primarily use this information to improve the study center and enhance elements users spend most time on.
 * We will record chat history to improve the AI to be more effective and targeted for user needs. Additionally, any behavior that goes against user policy in the discuss feature will be tied to your account and may lead to suspension of your account.


### Verifying Effectiveness
To verify the effectiveness of the study center, we could ask for user feedback in pop-up surveys. There could also be a small-scale study comparing in-person students of the Duke course, in-person students of the course with this supplement, and online-only users. Their understanding of the course would be evaluated through open-ended discussions or writing.


### Feedback and Discussion
* For my initial wireframe, I got feedback that the text boxes for the discuss function got convoluted since I designed them as speech bubbles coming from the 2 users and the AI. I ended up doing a simulation of a chat, so this concern was resolved.
* I also received feedback to establish more rules for discussion chats, so I included a user policy in the blurb of the discuss feature: "User policy: Users must maintain respectful conduct in all interactions. Harassment, hate speech, or any form of offensive behavior is strictly prohibited." I didn't want to prohibit the sharing of personal information since people may want to find ways to chat outside of the study center.
* At first, I got some feedback that the questions generated were too generic, so I added more sample assessments for the AI to train on.
* I got feedback that the homepage looked funny, but I decided not to spend too much time on it.
* To work around difficulties related to the discuss feature, Prof. Duvall suggested that I simulate a chat between students by having the user pretend to be each student. I implemented this suggestion by having the 2 theoretical students differentiate themselves as "S1:" and "S2:" in the chat with the AI mod.
* There was some confusion about ways to assess online students' knowledge. I decided that there wouldn't be quizzes for them since users would mostly be learning for personal interest and not for any sort of credential. In the future, there could be a section for users to write blogs that would unlock accessories for their avatars.


### How the Project Evolved
Initially, I wanted to create an online learning experience for AP Art History that contained a textbook/article section as well as an AI tutor, chat with other students, and notes center. Prof. Duvall suggested that I work with Sofa since our topics aligned, so we pivoted to combining our basic ideas to create a study center and textbook for a class we both took. I got rid of the textbook part on my end and kept the other three ideas for features. Initially, I wanted the AI chats to appear as speech bubbles coming from the users' avatars, but I decided to focus on the AI itself and not implement the visual elements. I also didn't implement the customizable avatars (the more discussions you participate in, the more accessories you unlock) since it would take time to illustrate them. I also didn't get a chance to implement the notes since we couldn't find a way to directly connect the notes from Sofa's Snapchat AR to the site. I also implemented Prof. Duvall's suggestion on the discussion function as mentioned above.
