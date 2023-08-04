# FairHire
# Link : https://fair-hire.vercel.app/

Discription : 

Page
1. Introduction
1. 1 Purpose
The purpose of this document is to develop a website which helps the ministry
to fight against discrimination at the workplace. People can get instant help
through this website by chatting with ministry’s employee and also they can
file a complaint against someone who discriminated against them.
1.2 Scope
Many people feel discrimination at the job interviews. They are not being hired
due to their race, nationality, gender etc. This should be prevented and for
that these complaints should be notified to the government so that they can
take actions on these companies. Hence ,Our website will be a medium
through which anyone will be able to get assistance regarding their queries
related to discrimination. They will also be able to file a complaint about the
incident with detailed explanation.
1.3 Intended Audience
Our intended audience is people who work in companies or want to work
anywhere. Anyone who did not get a chance of a better opportunity due to
their race, nationality, gender etc. Also anyone who just wants to know the
laws and regulations against discrimination.
1.4 Abbreviation and acronyms
e.g ( As an Example )
etc ( And Many Others )
2. Overall Descriptions
2.1 Product Perspective
This product helps the ministry to fight against discrimination at the
workplace. People can get instant help through this website by chatting
with ministry’s employee and also they can file a complaint against
someone who discriminated against them.
2.2 Product Function
Admin User: The Admin user is the super user and has control over all
the activities that can be done. The Admin user has the authority to
delete user or add user and put restrictions on the user. It has access
to all the data and statistics of the organization.
Chat Staff User: The Chat Staff user has control over chat section of
the website. Here chat staff can chat with general user.
Staff User: The Staff user sees the complaints details which are
assigned to them. They can add comments to the complain and
change status of the complaint.
General User: User who files the complaint. This user get the
notification whenever the status of the complaint is changed or
whenever new comment is added.
User Complaint Function:
a. User visits the website and clicks on the complaint tab.
b. The user is redirected to a complaint form where they can fill out the
necessary details of their complaint.
c. After submitting the form, the user receives a unique complaint token
via email.
d. The user can use this token to check the status of their complaint.
Check Complaint Function:
a. A user visits the website and clicks on the check complaint tab.
b. In order to check the status of their complaint, the user enters their
6-digit token number and email address.
c. If the complaint has been resolved, the user can view the resolution
details.
Know About Laws Function:
a. User visits the website and clicks on the "laws and regulation" page
or initiates a chat with the chatbot.
b. The user can learn about the existing laws related to discrimination.
One-to-One Chat Function:
a. When User visits the website and clicks on the chat tab.
b. A dialog popup appears and the user enters their name to start the
chat.
c. The user is assigned to a chat staff member who helps resolve their
query.
d. The user can end the chat by clicking on the "Resolved chat" button
whenever the query is resolved. This can be done from ministry end as
well.
Bilingual Function:
a. The user can change the language of the website to French or
English by clicking on the translate button.
Admin Function:
a. Admin has access to all completed complaints and can sort them
based on their status.
b. The administrator can create new users and assign them roles as
needed.
c. Admin has access to statistical analysis of complaints.
Chat Staff User Function:
a. The chat staff user logs in and sees the pending chat requests.
b. By clicking on the "View Chat" button, the chat staff user can view
and resolve chat requests.
c. By clicking on the "Resolved chat" button, the chat staff user can end
the chat.
Staff User Function:
a. The staff user when login to their account and can see all the
complaints assigned to them.
b. The staff user can change the status of a complaint by selecting the
appropriate option from the dropdown(Resolved, Pending. In progress).
c. The staff user can view the details of a complaint and add comments
whenever required.
d. Whenever the status of a complaint is changed, an email is sent to
the user to notify them of the update.
2.3 User Characteristics
1. User should be familiar with how websites work.
2. User should be familiar with technology.
3. User should be able to understand either French or English.
2.4 Operating Environment
This website will work in any browser and any operation system.
2.5 Diagrams
2.5.1 Flow Chart
2.5.2 Use Case Diagram
2.5.3 Sequence Diagram
3. Functional Requirements
3.1 User Side Requirements
1. They should be able to get information about laws and regulations.
2. They should be able to get tips about discrimination.
3. They should be able to chat with staff members.
4. They should be able to file a complaint to the ministry.
5. They should be able to file a complaint without being logged in.
6. They should be able to view his complaint by the token provided when
he filed his complete.
7. These fields should be in the complaint form: FirstName, LastName,
Email, Mobile No, Type of Discrimination, Company, City, Province,
Postal Code, Date, Description.
8. The website should be available in French and English both languages.
9. In chat, the website must show the user's current number in the Chat
Staff’s chat list.
10.They should be able to see the ministry’s comments on their complaint.
11. They should be able to delete their complaint.
3.2 Staff Side Requirement
1. They should be able to see a list of complaints.
2. They should be able to filter the list based on its current status.
3. They should be able to view the full details of a particular complaint.
4. They should not be able to view the statistics.
5. They should be able to change the status of the complaint.
6. They should be able to provide a comment on a complaint which the
user can also see.
7. A new complaint must be assigned to a staff member who has the least
complaints.
8. They should be able to delete the comments on a complaint.
9. They should be provided a new password on their provided mail if they
forget their password.
3.3 Chat Staff Side Requirements
1. They should be able to see a list of complaints.
2. They should not be able to view the statistics.
3. They should be able to chat with users.
4. They should be able to resolve a complaint.
5. A new chat must be assigned to a chat staff member who has the least
chats.
6. They should be provided a new password on their provided mail if they
forget their password.
3.4 Admin ( Minister ) Side Requirements
1. They should be able to see a list of complaints.
2. They should be able to filter the list based on its current status.
3. They should be able to view the full details of a particular complaint.
4. They should be able to view the statistics on the basis of city, state,
company and status.
5. They should not be able to change the status of their complaint.
6. They should be able to provide a comment on a complaint which the
user can also see.
7. They should be able to add a new Admin, staff member and a chat staff
member.
8. They should be able to delete the comments on a complaint.
9. They Should be provided a new password on their provided mail if they
forget their password.
4. Non Functional Requirements:
4.1 Performance
Develop a website which can be easily used by many users at a time
and can also work well with moderate speed internet connection.
4.2 Security
Website data must be kept safe and only authorised users should have
access to it. E.g. Only a person who filed a complaint should be able to
see the details besides ministry members.
4.3 Usability
Websites must have good navigation through which users can navigate
through different features of the website. It should also be
responsive,which means it should work well in mobile phones, tablets
and laptops.
4.4 Portability
The website should be used on any platform like windows, mac, linux
and also in any browser like mozilla firefox, chrome and safari.
4.5 Error Handling
The website must have error handling which means any unexpected
behaviour of the user should not harm the website’s workflow.
5. Interfaces
5.1 User Interfaces
5.1.1 Home Page
A home page of this website basically provides an intro of a website to
users. It also gives a feature of Chat with AI, through which he can get
information regarding discrimination.
5.1.2 Complaint Page
Through complaint page, user can file a new complaint against the
company and also can track the progress of already files complaints.
5.1.3 About Page
Through about page, user can get to know about the moto of fairhire.
5.1.4 Laws and Regulations Page
Through this page, user can learn the laws and Regulations against
discrimination.
5.1.5 Chat with Ministry Employees Page
Through this page, user can communicate with ministry employees and ask
any question related to discrimination.
5.2 Ministry Interfaces
5.2.1 Minister ( Admin ) Interfaces
5.2.1.1 Dashboard Page
Through this page minster can check all the complaints with
full details and also can filter the list. They can also add
comments on specific complaint.
5.2.1.2 Statistics page
Through this page minister can get the statistics about the
complaints.
5.2.1.3 Add User page
Through this page minister can add new admin, chat staff and
staff member.
5.2.2 Staff Interfaces
5.2.2.1 Dashboard Page
Through this page employees can check all the complaints
with full details and also can filter the list. They can also
change the status of any complaints as well as can add
comments.
5.2.3 Chat Staff Interfaces
5.2.3.1 Chat with user Page
Through this page, chat staff can chat with users and can
answer their questions.
