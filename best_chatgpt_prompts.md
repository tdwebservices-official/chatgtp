# Mind-Bending ChatGPT Prompts

# Coding

1.  Act as Solr Search Engine
    1.  I want you to act as a Solr Search Engine running in standalone mode. You will be able to add inline JSON documents in arbitrary fields and the data types could be of integer, string, float, or array. Having a document insertion, you will update your index so that we can retrieve documents by writing SOLR specific queries between curly braces by comma separated like {q='title:Solr', sort='score asc'}. You will provide three commands in a numbered list. First command is "add to" followed by a collection name, which will let us populate an inline JSON document to a given collection. Second option is "search on" followed by a collection name. Third command is "show" listing the available cores along with the number of documents per core inside round bracket. Do not write explanations or examples of how the engine work. Your first prompt is to show the numbered list and create two empty collections called 'prompts' and 'eyay' respectively.

  

3.  Act as senior front end developer
    1.  I want you to act as a Senior Frontend developer. I will describe a project details you will code project with this tools: Create React App, yarn, Ant Design, List, Redux Toolkit, createSlice, thunk, axios. You should merge files in single index.js file and nothing else. Do not write explanations. My first request is "Create Pokemon App that lists pokemons with images that come from PokeAPI sprites endpoint"

  

5.  Act as a PHP Interpreter
    1.  I want you to act like a php interpreter. I will write you the code and you will respond with the output of the php interpreter. I want you to only reply with the terminal output inside one unique code block, and nothing else. do not write explanations. Do not type commands unless I instruct you to do so. When i need to tell you something in english, i will do so by putting text inside curly brackets {like this}. My first command is

  

7.  Act as a Stackoverflow post
    1.  I want you to act as a stackoverflow post. I will ask programming-related questions and you will reply with what the answer should be. I want you to only reply with the given answer, and write explanations when there is not enough detail. do not write explanations. When I need to tell you something in English, I will do so by putting text inside curly brackets {like this}. My first question is "How do I read the body of an http.Request to a string in Golang"

  

9.  Act as R Programming Interpreter
    1.  I want you to act as a R interpreter. I'll type commands and you'll reply with what the terminal should show. I want you to only reply with the terminal output inside one unique code block, and nothing else. Do not write explanations. Do not type commands unless I instruct you to do so. When I need to tell you something in english, I will do so by putting text inside curly brackets {like this}. My first command is "sample(x = 1:10, size = 5)"

  

11.  Act as a Regex generator
    1.  I want you to act as a regex generator. Your role is to generate regular expressions that match specific patterns in text. You should provide the regular expressions in a format that can be easily copied and pasted into a regex-enabled text editor or programming language. Do not write explanations or examples of how the regular expressions work; simply provide only the regular expressions themselves. My first prompt is to generate a regular expression that matches an email address.

  

13.  Act as an IT Expert
    1.  I want you to act as an IT Expert. I will provide you with all the information needed about my technical problems, and your role is to solve my problem. You should use your computer science, network infrastructure, and IT security knowledge to solve my problem. Using intelligent, simple, and understandable language for people of all levels in your answers will be helpful. It is helpful to explain your solutions step by step and with bullet points. Try to avoid too many technical details, but use them when necessary. I want you to reply with the solution, not write any explanations. My first problem is “my laptop gets an error with a blue screen.”

  

15.  Act as a Full-Stack Software Developer
    1.  I want you to act as a software developer. I will provide some specific information about a web app requirements, and it will be your job to come up with an architecture and code for developing secure app with Golang and Angular. My first request is 'I want a system that allow users to register and save their vehicle information according to their roles and there will be admin, user and company roles. I want the system to use JWT for security'.

  

17.  Act as an SVG Designer
    1.  I would like you to act as an SVG designer. I will ask you to create images, and you will come up with SVG code for the image, convert the code to a base64 data url and then give me a response that contains only a markdown image tag referring to that data url. Do not put the markdown inside a code block. Send only the markdown, so no text. My first request is: give me an image of a red circle.

  

19.  Act as a machine learning engineer
    1.  I want you to act as a machine learning engineer. I will write some machine learning concepts and it will be your job to explain them in easy-to-understand terms. This could contain providing step-by-step instructions for building a model, demonstrating various techniques with visuals, or suggesting online resources for further study. My first suggestion request is "I have a dataset without labels. Which machine learning algorithm should I use?"
    
      
    
20.  Act as a python interpreter
    1.  I want you to act like a Python interpreter. I will give you Python code, and you will execute it. Do not provide any explanations. Do not respond with anything except the output of the code. The first code is: "print('hello world!')"
    
      
    
21.  Act as a Tech Writer
    1.  Act as a tech writer. You will act as a creative and engaging technical writer and create guides on how to do different stuff on specific software. I will provide you with basic steps of an app functionality and you will come up with an engaging article on how to do those basic steps. You can ask for screenshots, just add (screenshot) to where you think there should be one and I will add those later. These are the first basic steps of the app functionality: "[1.Click](http://1.Click) on the download button depending on your platform 2.Install the file. 3.Double click to open the app"
    
      
    
22.  Act an IT Architect
    1.  I want you to act as an IT Architect. I will provide some details about the functionality of an application or other digital product, and it will be your job to come up with ways to integrate it into the IT landscape. This could involve analyzing business requirements, performing a gap analysis and mapping the functionality of the new system to the existing IT landscape. Next steps are to create a solution design, a physical network blueprint, definition of interfaces for system integration and a blueprint for the deployment environment. My first request is "I need help to integrate a CMS system."
    
      
    
23.  Act as a SQL Terminal
    1.  I want you to act as a SQL terminal in front of an example database. The database contains tables named "Products", "Users", "Orders" and "Suppliers". I will type queries and you will reply with what the terminal would show. I want you to reply with a table of query results in a single code block, and nothing else. Do not write explanations. Do not type commands unless I instruct you to do so. When I need to tell you something in English I will do so in curly braces {like this). My first command is 'SELECT TOP 10 \* FROM Products ORDER BY Id DESC'
    
      
    
24.  Act as a software quality assurance tester
    1.  I want you to act as a software quality assurance tester for a new software application. Your job is to test the functionality and performance of the software to ensure it meets the required standards. You will need to write detailed reports on any issues or bugs you encounter, and provide recommendations for improvement. Do not include any personal opinions or subjective evaluations in your reports. Your first task is to test the login functionality of the software.
    
      
    
25.  Act as a web design consultant
    1.  I want you to act as a web design consultant. I will provide you with details related to an organization needing assistance designing or redeveloping their website, and your role is to suggest the most suitable interface and features that can enhance user experience while also meeting the company's business goals. You should use your knowledge of UX/UI design principles, coding languages, website development tools etc., in order to develop a comprehensive plan for the project. My first request is "I need help creating an e-commerce site for selling jewelry."
    
      
    
26.  Act as a cyber security specialist
    1.  I want you to act as a cyber security specialist. I will provide some specific information about how data is stored and shared, and it will be your job to come up with strategies for protecting this data from malicious actors. This could include suggesting encryption methods, creating firewalls or implementing policies that mark certain activities as suspicious. My first request is "I need help developing an effective cybersecurity strategy for my company."
    
      
    
27.  Act as a UI/UX Developer
    1.  I want you to act as a UX/UI developer. I will provide some details about the design of an app, website or other digital product, and it will be your job to come up with creative ways to improve its user experience. This could involve creating prototyping prototypes, testing different designs and providing feedback on what works best. My first request is "I need help designing an intuitive navigation system for my new mobile application."
    
      
    
28.  Act as a Linux Terminal
    1.  i want you to act as a linux terminal. I will type commands and you will reply with what the terminal should show. I want you to only reply with the terminal output inside one unique code block, and nothing else. do not write explanations. do not type commands unless I instruct you to do so. when i need to tell you something in english, i will do so by putting text inside curly brackets {like this}. my first command is pwd
    
      
    
29.  Act as a Javascript Console
    1.  I want you to act as a javascript console. I will type commands and you will reply with what the javascript console should show. I want you to only reply with the terminal output inside one unique code block, and nothing else. do not write explanations. do not type commands unless I instruct you to do so. when i need to tell you something in english, i will do so by putting text inside curly brackets {like this}. my first command is console.log("Hello World");

# Cooking

1.  Act as a Personal Chef
    1.  I want you to act as my personal chef. I will tell you about my dietary preferences and allergies, and you will suggest recipes for me to try. You should only reply with the recipes you recommend, and nothing else. Do not write explanations. My first request is "I am a vegetarian and I am looking for healthy dinner ideas."
    
      
    
2.  Act as a Chef
    1.  I require someone who can suggest delicious recipes that includes foods which are nutritionally beneficial but also easy & not time consuming enough therefore suitable for busy people like us among other factors such as cost effectiveness so overall dish ends up being healthy yet economical at same time! My first request – “Something light yet fulfilling that could be cooked quickly during lunch break”

# Education

1.  Act as an english pronounciation helper
    1.  I want you to act as an English pronunciation assistant for Turkish speaking people. I will write you sentences and you will only answer their pronunciations, and nothing else. The replies must not be translations of my sentence but only pronunciations. Pronunciations should use Turkish Latin letters for phonetics. Do not write explanations on replies. My first sentence is "how the weather is in Istanbul?"
    
      
    
2.  Act as a Plagiarism Checker
    1.  I want you to act as a plagiarism checker. I will write you sentences and you will only reply undetected in plagiarism checks in the language of the given sentence, and nothing else. Do not write explanations on replies. My first sentence is "For computers to behave like humans, speech recognition systems must be able to process nonverbal information, such as the emotional state of the speaker."
    
      
    
3.  Act as a debate coach
    1.  I want you to act as a debate coach. I will provide you with a team of debaters and the motion for their upcoming debate. Your goal is to prepare the team for success by organizing practice rounds that focus on persuasive speech, effective timing strategies, refuting opposing arguments, and drawing in-depth conclusions from evidence provided. My first request is "I want our team to be prepared for an upcoming debate on whether front-end development is easy."
    
      
    
4.  Act as a philosophy teacher
    1.  I want you to act as a philosophy teacher. I will provide some topics related to the study of philosophy, and it will be your job to explain these concepts in an easy-to-understand manner. This could include providing examples, posing questions or breaking down complex ideas into smaller pieces that are easier to comprehend. My first request is "I need help understanding how different philosophical theories can be applied in everyday life."
    
      
    
5.  Act as a Math Teacher
    1.  I want you to act as a math teacher. I will provide some mathematical equations or concepts, and it will be your job to explain them in easy-to-understand terms. This could include providing step-by-step instructions for solving a problem, demonstrating various techniques with visuals or suggesting online resources for further study. My first request is "I need help understanding how probability works."
    
      
    
6.  Act as an AI writing tutor
    1.  I want you to act as an AI writing tutor. I will provide you with a student who needs help improving their writing and your task is to use artificial intelligence tools, such as natural language processing, to give the student feedback on how they can improve their composition. You should also use your rhetorical knowledge and experience about effective writing techniques in order to suggest ways that the student can better express their thoughts and ideas in written form. My first request is "I need somebody to help me edit my master's thesis."
    
      
    
7.  Act as an Etymologist
    1.  I want you to act as a etymologist. I will give you a word and you will research the origin of that word, tracing it back to its ancient roots. You should also provide information on how the meaning of the word has changed over time, if applicable. My first request is "I want to trace the origins of the word 'pizza'."
    
      
    
8.  Act as a Career Counselor
    1.  I want you to act as a career counselor. I will provide you with an individual looking for guidance in their professional life, and your task is to help them determine what careers they are most suited for based on their skills, interests and experience. You should also conduct research into the various options available, explain the job market trends in different industries and advice on which qualifications would be beneficial for pursuing particular fields. My first request is "I want to advise someone who wants to pursue a potential career in software engineering."
    
      
    
9.  Act as a fill in the blank worksheet generator
    1.  I want you to act as a fill in the blank worksheets generator for students learning English as a second language. Your task is to create worksheets with a list of sentences, each with a blank space where a word is missing. The student's task is to fill in the blank with the correct word from a provided list of options. The sentences should be grammatically correct and appropriate for students at an intermediate level of English proficiency. Your worksheets should not include any explanations or additional instructions, just the list of sentences and word options. To get started, please provide me with a list of words and a sentence containing a blank space where one of the words should be inserted.
    
      
    
10.  Act as an instructor in school
    1.  I want you to act as an instructor in a school, teaching algorithms to beginners. You will provide code examples using python programming language. First, start briefly explaining what an algorithm is, and continue giving simple examples, including bubble sort and quick sort. Later, wait for my prompt for additional questions. As soon as you explain and give the code samples, I want you to include corresponding visualizations as an ascii art whenever possible.
    
      
    
11.  Act as an academician
    1.  I want you to act as an academician. You will be responsible for researching a topic of your choice and presenting the findings in a paper or article form. Your task is to identify reliable sources, organize the material in a well-structured way and document it accurately with citations. My first suggestion request is "I need help writing an article on modern trends in renewable energy generation targeting college students aged 18-25."
    
      
    
12.  Act as a fallacy finder
    1.  I want you to act as a fallacy finder. You will be on the lookout for invalid arguments so you can call out any logical errors or inconsistencies that may be present in statements and discourse. Your job is to provide evidence-based feedback and point out any fallacies, faulty reasoning, false assumptions, or incorrect conclusions which may have been overlooked by the speaker or writer. My first suggestion request is "This shampoo is excellent because Cristiano Ronaldo used it in the advertisement."
    
      
    
13.  Act as a Socrat
    1.  I want you to act as a Socrat. You will engage in philosophical discussions and use the Socratic method of questioning to explore topics such as justice, virtue, beauty, courage and other ethical issues. My first suggestion request is "I need help exploring the concept of justice from an ethical perspective."
    
      
    
14.  Act as Educational Content Creator
    1.  I want you to act as an educational content creator. You will need to create engaging and informative content for learning materials such as textbooks, online courses and lecture notes. My first suggestion request is "I need help developing a lesson plan on renewable energy sources for high school students."
    
      
    
15.  Act as an Essay Writer
    1.  I want you to act as an essay writer. You will need to research a given topic, formulate a thesis statement, and create a persuasive piece of work that is both informative and engaging. My first suggestion request is “I need help writing a persuasive essay about the importance of reducing plastic waste in our environment”.
    
      
    
16.  Act as an elocutionist
    1.  I want you to act as an elocutionist. You will develop public speaking techniques, create challenging and engaging material for presentation, practice delivery of speeches with proper diction and intonation, work on body language and develop ways to capture the attention of your audience. My first suggestion request is "I need help delivering a speech about sustainability in the workplace aimed at corporate executive directors".
    
      
    
17.  Act as a historian
    1.  I want you to act as a historian. You will research and analyze cultural, economic, political, and social events in the past, collect data from primary sources and use it to develop theories about what happened during various periods of history. My first suggestion request is "I need help uncovering facts about the early 20th century labor strikes in London."
    
      
    
18.  Act as a public speaking coach
    1.  I want you to act as a public speaking coach. You will develop clear communication strategies, provide professional advice on body language and voice inflection, teach effective techniques for capturing the attention of their audience and how to overcome fears associated with speaking in public. My first suggestion request is "I need help coaching an executive who has been asked to deliver the keynote speech at a conference."
    
      
    
19.  Act as a biblical translator
    1.  I want you to act as an biblical translator. I will speak to you in english and you will translate it and answer in the corrected and improved version of my text, in a biblical dialect. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, biblical words and sentences. Keep the meaning same. I want you to only reply the correction, the improvements and nothing else, do not write explanations. My first sentence is "Hello, World!"
    
      
    
20.  Act as a mathematician
    1.  I want you to act like a mathematician. I will type mathematical expressions and you will respond with the result of calculating the expression. I want you to answer only with the final amount and nothing else. Do not write explanations. When I need to tell you something in English, I'll do it by putting the text inside square brackets {like this}. My first expression is: 4+5
    
      
    
21.  Act as a Talent Coach
    1.  I want you to act as a Talent Coach for interviews. I will give you a job title and you'll suggest what should appear in a curriculum related to that title, as well as some questions the candidate should be able to answer. My first job title is "Software Engineer".

# Copywriting

1.  "I'm looking for a \[type of text\] that will speak directly to the needs and pain points of my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and strong offer."

  

3.  "I need a \[type of text\] that will showcase the value and benefits of my \[product/service\] to \[ideal customer persona\] and convince them to take \[desired action\] with social proof and credibility-building elements."

  

5.  "I'm looking for a \[type of text\] that will clearly explain the features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase with a strong call-to-action."

  

7.  "I need a \[type of text\] that will make my \[ideal customer persona\] feel \[emotion\] about my \[product/service\] and persuade them to take \[desired action\] with a sense of urgency."

  

9.  "I'm looking for a \[type of text\] that will establish trust and credibility with my \[ideal customer persona\] by highlighting the successes and testimonials of previous customers who have used my \[product/service\]."

  

11.  "I need a \[type of text\] that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\]."

  

13.  "I'm looking for a \[type of text\] that will showcase the unique features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase."

  

15.  "I need a \[type of text\] that will tell a story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\] in a relatable and engaging way."

  

17.  "I'm looking for a \[type of text\] that will draw in my \[ideal customer persona\] with a strong headline and hook, and then convince them to take \[desired action\] with persuasive language and compelling evidence."

  

19.  "I need a \[type of text\] that will address the pain points and needs of my \[ideal customer persona\] and show them how my \[product/service\] is the solution they've been searching for."

  

21.  "I'm looking for a \[type of text\] that will explain the features and benefits of my \[product/service\] to \[ideal customer persona\] in a clear and concise manner, leading them to make a purchase."

  

23.  "I need a \[type of text\] that will make my \[ideal customer persona\] feel \[emotion\] about my \[product/service\] and convince them to take \[desired action\]."

  

25.  "I'm looking for a \[type of text\] that will convince \[ideal customer persona\] to sign up for my \[program/subscription\] by explaining the value it brings and the benefits they'll receive."

  

27.  "I need a \[type of text\] that will persuade \[ideal customer persona\] to purchase my \[product/service\] by highlighting its unique benefits and addressing any potential objections."

  

29.  "Please write a compelling \[type of text\] that speaks directly to my \[ideal customer persona\] and encourages them to take \[desired action\] on my \[website/product\]."

# Email Marketing

1.  "I need a \[type of email\] that will persuade my \[ideal customer persona\] to purchase my \[product/service\] by highlighting its unique benefits and addressing any potential objections."

  

3.  "I'm looking for a \[type of email\] that will convince my \[ideal customer persona\] to sign up for my \[program/subscription\] by explaining the value it brings and the benefits they'll receive."

  

5.  "I need a \[type of email\] that will make my \[ideal customer persona\] feel \[emotion\] about my \[product/service\] and convince them to take \[desired action\]."

  

7.  "I'm looking for a \[type of email\] that will explain the features and benefits of my \[product/service\] to \[ideal customer persona\] in a clear and concise manner, leading them to make a purchase."

  

9.  "I need a \[type of email\] that will address the pain points and needs of my \[ideal customer persona\] and show them how my \[product/service\] is the solution they've been searching for."

  

11.  "I'm looking for a \[type of email\] that will draw in my \[ideal customer persona\] with a strong headline and hook, and then convince them to take \[desired action\] with persuasive language and compelling evidence."

  

13.  "I need a \[type of email\] that will tell a story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\] in a relatable and engaging way."

  

15.  "I'm looking for a \[type of email\] that will showcase the unique features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase."

  

17.  "I need a \[type of email\] that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\]."

  

19.  "I'm looking for a \[type of email\] that will establish trust and credibility with my \[ideal customer persona\] by highlighting the successes and testimonials of previous customers who have used my \[product/service\]."
20.  "I need a \[type of email\] that will make my \[ideal customer persona\] feel \[emotion\] about my \[product/service\] and persuade them to take \[desired action\] with a sense of urgency."

  

22.  "I'm looking for a \[type of email\] that will clearly explain the features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase with a strong call-to-action."

  

24.  "I need a \[type of email\] that will showcase the value and benefits of my \[product/service\] to \[ideal customer persona\] and convince them to take \[desired action\] with social proof and credibility building elements."

  

26.  "I'm looking for a \[type of email\] that will speak directly to the needs and pain points of my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and strong offer."

  

28.  "I need a \[type of email\] that will convince my \[ideal customer persona\] to purchase my \[product/service\] by highlighting its unique benefits and addressing any potential objections."

# Blog Writing

1.  "I'm looking for a \[type of blog post\] that will engage my \[ideal customer persona\] with a unique and compelling perspective on \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

3.  "I need a \[type of blog post\] that will provide valuable and relevant information to my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[website/product\]."

  

5.  "I'm looking for a \[type of blog post\] that will educate my \[ideal customer persona\] on a specific \[topic\] and persuade them to take \[desired action\] on my \[website/product\]."

  

7.  "I need a \[type of blog post\] that will speak directly to the needs and pain points of my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and strong offer."

  

9.  "I'm looking for a \[type of blog post\] that will showcase the value and benefits of my \[product/service\] to \[ideal customer persona\] and convince them to take \[desired action\] with social proof and credibility-building elements."

  

11.  "I need a \[type of blog post\] that will tell a story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\] in a relatable and engaging way."

  

13.  "I need a \[type of blog post\] that will tell a story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\] in a relatable and engaging way."

  

15.  "I'm looking for a \[type of blog post\] that will draw in my \[ideal customer persona\] with a strong headline and hook, and then convince them to take \[desired action\] with persuasive language and compelling evidence."

  

17.  "I need a \[type of blog post\] that will address the pain points and needs of my \[ideal customer persona\] and show them how my \[product/service\] is the solution they've been searching for."

  

19.  "I'm looking for a \[type of blog post\] that will clearly explain the features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase with a strong call-to-action."

  

21.  "I need a \[type of blog post\] that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\]."

  

23.  "I'm looking for a \[type of blog post\] that will showcase the unique features and benefits of my \[product/service\] to \[ideal customer persona\] and persuade them to make a purchase."

  

25.  "I need a \[type of blog post\] that will make my \[ideal customer persona\] feel \[emotion\] about my \[product/service\] and persuade them to take \[desired action\] with a sense of urgency."

  

27.  "I'm looking for a \[type of blog post\] that will establish trust and credibility with my \[ideal customer persona\] by highlighting the successes and testimonials of previous customers who have used my \[product/service\]."

  

29.  "I need a \[type of blog post\] that will convince my \[ideal customer persona\] to purchase my \[product/service\] by highlighting its unique benefits and addressing any potential objections."

  

31.  "I'm looking for a \[type of blog post\] that will speak directly to my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[website/product\]."

# Influencer Marketing

1.  "I'm looking for an influencer marketing campaign outline that will target my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can provide valuable and relevant information about our \[product/service\] and encourage them to take \[desired action\]."

  

3.  "I need an influencer marketing campaign outline that will use the authenticity and relatability of \[influencer type\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on our \[product/service\]."

  

5.  "I'm looking for an influencer marketing campaign outline that will leverage the social proof and credibility of \[influencer type\] to persuade my \[ideal customer persona\] to try our \[product/service\] and share their positive experience with their followers."

  

7.  "I need an influencer marketing campaign outline that will engage my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can showcase the unique features and benefits of our \[product/service\] in a fun and creative way."

  

9.  "I'm looking for an influencer marketing campaign outline that will use the influence and reach of \[influencer type\] to drive traffic and sales to our \[product/service\] for my \[ideal customer persona\]."

  

11.  "I need an influencer marketing campaign outline that will leverage the authority and expertise of \[influencer type\] to educate my \[ideal customer persona\] on the benefits of our \[product/service\] and persuade them to make a purchase."

  

13.  "I'm looking for an influencer marketing campaign outline that will target my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can share valuable and relevant information about our \[product/service\] and encourage them to take \[desired action\]."

  

15.  "I need an influencer marketing campaign outline that will leverage the authenticity and relatability of \[influencer type\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on our \[product/service\]."

  

17.  "I'm looking for an influencer marketing campaign outline that will use the social proof and credibility of \[influencer type\] to persuade my \[ideal customer persona\] to try our \[product/service\] and share their positive experience with their followers."

  

19.  "I need an influencer marketing campaign outline that will create a sense of urgency and FOMO for my \[ideal customer persona\] by featuring \[influencer type\] who can share exclusive deals and promotions for our \[product/service\]."

  

21.  "I'm looking for an influencer marketing campaign outline that will leverage the reach and influence of \[influencer type\] to drive awareness and sales of our \[product/service\] to my \[ideal customer persona\]."

  

23.  "I need an influencer marketing campaign outline that will engage my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can showcase the unique features and benefits of our \[product/service\] in a compelling and authentic way."

  

25.  "I'm looking for an influencer marketing campaign outline that will leverage the authority and credibility of \[influencer type\] to persuade my \[ideal customer persona\] to try our \[product/service\] and share their positive experience with their followers."

  

27.  "I need an influencer marketing campaign outline that will target my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can authentically share the benefits of our \[product/service\] and encourage them to make a purchase."

  

29.  "I'm looking for an influencer marketing campaign outline that will showcase my \[product/service\] to my \[ideal customer persona\] and persuade them to take \[desired action\] with the help of \[influencer type\] who aligns with our brand values."

# Youtube Ad Scripts

1.  "I need a YouTube ad script that will showcase the unique selling points of my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with a sense of urgency and exclusive offers."

  

3.  "I'm looking for a YouTube ad script that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

5.  "I'm looking for a YouTube ad script that will establish trust and credibility with my \[ideal customer persona\] by highlighting the successes and testimonials of previous customers who have used my \[product/service\]."

  

7.  "I need a YouTube ad script that will educate my \[ideal customer persona\] on a specific \[topic\] and persuade them to take \[desired action\] on my \[website/product\]."

  

9.  "I'm looking for a YouTube ad script that will speak directly to the needs and pain points of my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and strong offer."

  

11.  "I need a YouTube ad script that will provide valuable and relevant information to my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[website/product\]."

  

13.  "I'm looking for a YouTube ad script that will engage my \[ideal customer persona\] with a unique and compelling perspective on \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

15.  "I need a YouTube ad script that will address the pain points and needs of my \[ideal customer persona\] and show them how my \[product/service\] is the solution they've been searching for."

  

17.  "I'm looking for a YouTube ad script that will clearly explain the features and benefits of my \[product/service\] to my \[ideal customer persona\] and persuade them to make a purchase with a sense of urgency."

  

19.  "I need a YouTube ad script that will tell a story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\] in a relatable and engaging way."

  

21.  "I'm looking for a YouTube ad script that will showcase the value and benefits of my \[product/service\] to my \[ideal customer persona\] and persuade them to take \[desired action\] with a strong offer and clear call-to-action."

  

23.  "I need a YouTube ad script that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\] with a sense of urgency."

  

25.  "I'm looking for a YouTube ad script that will draw in my \[ideal customer persona\] with a strong headline and hook, and then convince them to take \[desired action\] with persuasive language and compelling evidence."

  

27.  "I need a YouTube ad script that will showcase the unique features and benefits of my \[product/service\] to my \[ideal customer persona\] and persuade them to make a purchase with social proof and credibility-building elements."

  

29.  "I'm looking for a YouTube ad script that will introduce my \[product/service\] to my \[ideal customer persona\] and persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

# Facebook Ad Copy

1.  "I need a Facebook ad copy that will engage my \[ideal customer persona\] with \[specific type of content\] from \[influencer type\] who can authentically share the benefits of my \[product/service\] and encourage them to make a purchase."

  

3.  "I'm looking for a Facebook ad copy that will use the social proof and credibility of \[influencer type\] to persuade my \[ideal customer persona\] to try my \[product/service\] and share their positive experience with their followers."

  

5.  "I need a Facebook ad copy that will leverage the reach and influence of \[influencer type\] to drive traffic and sales to my \[product/service\] for my \[ideal customer persona\]."

  

7.  "I'm looking for a Facebook ad copy that will create a sense of community and belonging for my \[ideal customer persona\] by featuring user-generated content and encouraging them to share their own experiences with my \[product/service\] with the help of \[influencer type\]."

  

9.  "I need a Facebook ad copy that will leverage the authority and credibility of \[influencer type\] to educate my \[ideal customer persona\] on the benefits of my \[product/service\] and persuade them to try it out for themselves."

  

11.  "I'm looking for a Facebook ad copy that will use the influence and reach of \[influencer type\] to showcase the unique features and benefits of my \[product/service\] to my \[ideal customer persona\] and encourage them to make a purchase."

  

13.  "I need a Facebook ad copy that will create a sense of urgency and FOMO for my \[ideal customer persona\] by featuring exclusive deals and promotions for my \[product/service\]."

  

15.  "I need a Facebook ad copy that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[product/service\]."

  

17.  "I'm looking for a Facebook ad copy that will leverage the social proof and credibility of my \[brand/company\] to persuade my \[ideal customer persona\] to try my \[product/service\] and share their positive experience with their followers."

  

19.  "I need a Facebook ad copy that will engage my \[ideal customer persona\] with a unique and creative visual campaign that showcases the features and benefits of my \[product/service\] in a compelling way."

  

21.  "I'm looking for a Facebook ad copy that will use the influence and reach of my \[brand/company\] to drive traffic and sales to my \[product/service\] for my \[ideal customer persona\]."

  

23.  "I need a Facebook ad copy that will leverage the authority and expertise of my \[brand/company\] to educate my \[ideal customer persona\] on the benefits of my \[product/service\] and persuade them to make a purchase."

  

25.  "I'm looking for a Facebook ad copy that will provide a sneak peek of upcoming products or services and create a sense of anticipation and excitement for my \[ideal customer persona\] with a clear and compelling call-to-action."

  

27.  "I need a Facebook ad copy that will create a sense of community and belonging for my \[ideal customer persona\] by featuring user-generated content and encouraging them to share their own experiences with my \[product/service\]."

  

29.  "I'm looking for a Facebook ad copy that will showcase the unique and personal experiences of my \[ideal customer persona\] with my \[product/service\] and persuade them to share their positive review with their followers."

# Youtube Video Ideas

1.  "I need a YouTube video idea that will provide a behind-the-scenes look at my \[company/brand\] and persuade my \[ideal customer persona\] to take \[desired action\] with a sense of authenticity and relatability."

  

3.  "I'm looking for a YouTube video idea that will provide a step-by-step guide on how to use my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with clear and compelling instructions."

  

5.  "I need a YouTube video idea that will demonstrate how my \[product/service\] can solve the specific pain points and needs of my \[ideal customer persona\] in a relatable and engaging way."

  

7.  "I'm looking for a YouTube video idea that will showcase the unique selling points of my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with a sense of urgency and exclusive offers."

  

9.  "I need a YouTube video idea that will compare my \[product/service\] to similar options on the market and persuade my \[ideal customer persona\] to choose us with clear and compelling evidence."

  

11.  "I'm looking for a YouTube video idea that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

13.  "I need a YouTube video idea that will showcase the success stories of previous customers who have used my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase."

  

15.  "I need a YouTube video idea that will engage my \[ideal customer persona\] with a unique and compelling perspective on \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

17.  "I'm looking for a YouTube video idea that will provide valuable and relevant information to my \[ideal customer persona\] about \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

19.  "I need a YouTube video idea that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\] with a sense of urgency."

  

21.  "I'm looking for a YouTube video idea that will showcase the value and benefits of my \[product/service\] to my \[ideal customer persona\] and persuade them to take \[desired action\] with a strong offer and clear call-to-action."

  

23.  "I need a YouTube video idea that will showcase the unique features and benefits of my \[product/service\] in a fun and creative way, and persuade my \[ideal customer persona\] to make a purchase."

  

25.  "I'm looking for a YouTube video idea that will tell a unique and relatable story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\]."

  

27.  "I need a YouTube video idea that will both go viral and persuade my \[ideal customer persona\] to take \[desired action\] on my \[website/product\] with a strong call-to-action and compelling visuals."

  

29.  "I'm looking for a YouTube video idea that will go viral and showcase my \[product/service\] to my \[ideal customer persona\] in a creative and entertaining way."

# Twitter Thread Ideas

1.  "I'm looking for a Twitter thread idea that will provide a behind-the-scenes look at my \[company/brand\] and persuade my \[ideal customer persona\] to take \[desired action\] with a sense of authenticity and reliability."

  

3.  "I need a Twitter thread idea that will provide a step-by-step guide on how to use my \[product/service\] and attract high-quality leads with clear and compelling instructions."

  

5.  "I'm looking for a Twitter thread idea that will demonstrate how my \[product/service\] can solve the specific pain points and needs of my \[ideal customer persona\] in a relatable and engaging way."

  

7.  "I need a Twitter thread idea that will showcase the unique selling points of my \[product/service\] and attract high-quality leads with a sense of urgency and exclusive offers."

  

9.  "I'm looking for a Twitter thread idea that will compare my \[product/service\] to similar options on the market and persuade my \[ideal customer persona\] to choose us with clear and compelling evidence."

  

11.  "I need a Twitter thread idea that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

13.  "I'm looking for a Twitter thread idea that will establish trust and credibility with my \[ideal customer persona\] by showcasing the success stories of previous customers who have used my \[product/service\]."

  

15.  "I need a Twitter thread idea that will engage my \[ideal customer persona\] with a unique and compelling perspective on \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

17.  "I'm looking for a Twitter thread idea that will provide valuable and relevant information to my \[ideal customer persona\] about \[subject\] and attract high-quality leads with a strong call-to-action."

  

19.  "I need a Twitter thread idea that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\] with a sense of urgency."

  

21.  "I'm looking for a Twitter thread idea that will showcase the value and benefits of my \[product/service\] to my \[ideal customer persona\] and persuade them to take \[desired action\] with a clear and compelling message."

  

23.  "I need a Twitter thread idea that will showcase the unique features and benefits of my \[product/service\] in a fun and creative way, and attract high-quality leads with a strong offer."

  

25.  "I'm looking for a Twitter thread idea that will tell a unique and relatable story about my \[product/service\] and how it has helped \[ideal customer persona\] achieve their \[goal\]."

  

27.  "I need a Twitter thread idea that will both go viral and attract high-quality leads for my \[product/service\] with a strong call-to-action and compelling visuals."

  

29.  "I'm looking for a Twitter thread idea that will go viral and showcase my \[product/service\] to my \[ideal customer persona\] in a creative and engaging way."

# Instagram Story Ideas

1.  "I need an Instagram story idea that will provide a sneak peek of upcoming products or services and create a sense of anticipation and excitement for my \[ideal customer persona\] with a clear and compelling call-to-action."

  

3.  "I'm looking for an Instagram story idea that will create a sense of community and belonging for my \[ideal customer persona\] by featuring user-generated content and encouraging them to share their own experiences with my \[product/service\]."

  

5.  "I need an Instagram story idea that will showcase the unique and personal experiences of my \[ideal customer persona\] with my \[product/service\] and persuade them to share their positive review with their followers."

  

7.  "I need an Instagram story idea that will establish trust and credibility with my \[ideal customer persona\] by showcasing the expertise and professionalism of my \[company/brand\]."

  

9.  "I'm looking for an Instagram story idea that will provide a unique and compelling offer to my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and exclusivity."

  

11.  "I need an Instagram story idea that will demonstrate how my \[product/service\] can solve the specific pain points and needs of my \[ideal customer persona\] in a relatable and engaging way."

  

13.  "I'm looking for an Instagram story idea that will compare my \[product/service\] to similar options on the market and persuade my \[ideal customer persona\] to choose us with clear and compelling evidence."

  

15.  "I need an Instagram story idea that will leverage the social proof and credibility of previous customers to persuade my \[ideal customer persona\] to try my \[product/service\]."

  

17.  "I'm looking for an Instagram story idea that will provide a step-by-step guide on how to use my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with clear and compelling instructions."

  

19.  "I need an Instagram story idea that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

21.  "I'm looking for an Instagram story idea that will engage my \[ideal customer persona\] with behind-the-scenes content and persuade them to take \[desired action\] with a sense of exclusivity and authenticity."

  

23.  "I need an Instagram story idea that will showcase the success stories of previous customers who have used my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase."

  

25.  "I'm looking for an Instagram story idea that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\]."

  

27.  "I need an Instagram story idea that will provide valuable and relevant information to my \[ideal customer persona\] about \[subject\] and persuade them to take \[desired action\] with a clear and compelling message."

  

29.  "I'm looking for an Instagram story idea that will showcase the unique features and benefits of my \[product/service\] to my \[ideal customer persona\] in a creative and engaging way."

# Cold DM

1.  "I need a cold DM idea that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[product/service\]."

  

3.  "I need a cold DM idea that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[product/service\]."

  

5.  "I need a cold DM idea that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\] on my \[product/service\]."

  

7.  "I'm looking for a cold DM idea that will use the influence and reach of my \[brand/company\] to drive traffic and sales to my \[product/service\] for my \[ideal customer persona\]."

  

9.  "I need a cold DM idea that will leverage the authority and expertise of my \[brand/company\] to educate my \[ideal customer persona\] on the benefits of my \[product/service\] and persuade them to make a purchase."

  

11.  "I'm looking for a cold DM idea that will provide a sneak peek of upcoming products or services and create a sense of anticipation and excitement for my \[ideal customer persona\] with a clear and compelling call-to-action."

  

13.  "I need a cold DM idea that will create a sense of community and belonging for my \[ideal customer persona\] by featuring user-generated content and encouraging them to share their own experiences with my \[product/service\]."

  

15.  "I'm looking for a cold DM idea that will showcase the unique and personal experiences of my \[ideal customer persona\] with my \[product/service\] and persuade them to share their positive review with their followers."

  

17.  "I'm looking for a cold DM idea that will provide a step-by-step guide on how to use my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with clear and compelling instructions."

  

19.  "I need a cold DM idea that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

21.  "I'm looking for a cold DM idea that will engage my \[ideal customer persona\] with a unique and exclusive offer and persuade them to take \[desired action\] with a sense of urgency and exclusivity."

  

23.  "I need a cold DM idea that will showcase the success stories of previous customers who have used my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with a personalized message."

  

25.  "I'm looking for a cold DM idea that will leverage the authenticity and relatability of my \[brand/company\] to engage my \[ideal customer persona\] and persuade them to take \[desired action\]."

  

27.  "I need a cold DM idea that will provide valuable and relevant information to my \[ideal customer persona\] about \[subject\] and persuade them to take \[desired action\] with a personalized message."

  

29.  "I'm looking for a cold DM idea that will showcase the unique features and benefits of my \[product/service\] to my \[ideal customer persona\] in a clear and compelling way."

# Cold Emails

1.  "I need a cold email idea that will engage my \[ideal customer persona\] with a unique and compelling perspective on \[subject\] and persuade them to take \[desired action\] on my \[website/product\]."

  

3.  "I'm looking for a cold email idea that will establish trust and credibility with my \[ideal customer persona\] by showcasing the expertise and professionalism of my \[company/brand\]."

  

5.  "I need a cold email idea that will provide a unique and compelling offer to my \[ideal customer persona\] and persuade them to take \[desired action\] with a sense of urgency and exclusivity."

  

7.  "I'm looking for a cold email idea that will showcase the benefits and value of my \[product/service\] to my \[ideal customer persona\] and persuade them to make a purchase with a strong call-to-action."

  

9.  "I need a cold email idea that will use a personalized and targeted approach to engage my \[ideal customer persona\] and persuade them to take \[desired action\] with a clear and compelling message."

  

11.  "I need a cold email idea that will provide a behind-the-scenes look at my \[company/brand\] and persuade my \[ideal customer persona\] to take \[desired action\] with a sense of authenticity and relatability."

  

13.  "I'm looking for a cold email idea that will provide a step-by-step guide on how to use my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with clear and compelling instructions."

  

15.  "I need a cold email idea that will demonstrate how my \[product/service\] can solve the specific pain points and needs of my \[ideal customer persona\] in a relatable and engaging way."

  

17.  "I'm looking for a cold email idea that will showcase the unique selling points of my \[product/service\] and persuade my \[ideal customer persona\] to make a purchase with a sense of urgency and exclusive offers."

  

19.  "I need a cold email idea that will compare my \[product/service\] to similar options on the market and persuade my \[ideal customer persona\] to choose us with clear and compelling evidence."

  

21.  "I'm looking for a cold email idea that will draw in my \[ideal customer persona\] with a relatable and authentic message, and then persuade them to take \[desired action\] with a strong call-to-action and compelling visuals."

  

23.  "I need a cold email idea that will provide valuable and relevant information to my \[ideal customer persona\] about \[subject\] and persuade them to take \[desired action\] with a clear and compelling message."

  

25.  "I'm looking for a cold email idea that will overcome objections and concerns my \[ideal customer persona\] may have about my \[product/service\] and convince them to take \[desired action\] with a sense of urgency."

  

27.  "I need a cold email idea that will establish credibility and authority with my \[ideal customer persona\] by showcasing the success stories of previous customers who have used my \[product/service\]."

  

29.  "I'm looking for a cold email idea that will attract the attention of my \[ideal customer persona\] and persuade them to take \[desired action\] with a unique and compelling subject line."

# Mental Models

1.  "Please write a marketing campaign outline that addresses the Sunk Cost Fallacy when presenting our \[product/service\] to \[ideal customer persona\]. Consider how to frame the value of our offering in terms of future benefits, rather than past investments, and how to overcome any resistance to change or decision-making biases."

  

3.  "Please write a marketing campaign outline that takes the Law of Diminishing Returns into account when positioning our \[product/service\] for \[ideal customer persona\]. Consider how to optimize the value we offer for the cost, and how to communicate this value effectively to the target audience."

  

5.  "Please write a marketing campaign outline that leverages the Pareto Principle to identify the most important \[product/service features\] for \[ideal customer persona\] and focuses on maximizing the impact of these features. Consider how to prioritize the remaining \[20%/80%\] of features in a way that adds value to the customer experience."

  

7.  "Please write a marketing campaign outline that takes the Law of Diminishing Returns into account when positioning our \[product/service\] for \[ideal customer persona\]. Consider how to optimize the value we offer for the cost, and how to communicate this value effectively to the target audience."

  

9.  "Please write a marketing campaign outline that takes the Butterfly Effect into account when targeting \[ideal customer persona\] with our \[product/service\]. Consider how small changes or actions can have large and unpredictable impacts, and how to anticipate and manage these potential impacts."

  

11.  "Write a marketing campaign outline using The Pratfall Effect to create messaging and offers that highlight the imperfections or mistakes of the product or service in a humorous or self-deprecating way. Use this approach to make the product more relatable and appealing to the target audience, and to increase conversion rates."

  

13.  "Write a marketing campaign outline using The Principle of Least Effort to make the product or service as easy and convenient to use as possible. Identify ways to reduce the effort required by the target audience to adopt and use the product, and create messaging and offers that highlight these benefits in order to increase conversion rates."

  

15.  "Write a marketing campaign outline using the Anchoring and Adjustment Heuristic to present information in a logical and incremental way. Consider the audience's initial impressions and assumptions, and anchor the messaging and offers to these initial points. Then, make adjustments based on additional information in order to increase conversion rates."

  

17.  "Write a marketing campaign outline using the Representative Heuristic to appeal to the \[ideal customer persona\]. Identify the prototype or stereotype that represents the audience's expectations and experiences, and create messaging and offers that are similar to this prototype in order to increase conversion rates."

  

19.  "In order to avoid the Gambler's Fallacy, please write a marketing campaign outline that presents data and statistics in a meaningful and accurate way. Emphasize the importance of considering the full range of information and not relying on past performance as a guarantee of future results. Use data to demonstrate the effectiveness of the \[product/service\] and how it can help \[ideal customer persona\] achieve their \[goals\]."

  

21.  "Using the principle of marginal analysis, please outline a marketing campaign that considers the marginal cost and marginal benefit of various growth strategies. Identify the \[strategies\] being considered, and weigh the costs and benefits of each in terms of their impact on the overall \[objective\] of the campaign. Consider factors such as time, resources, and potential return on investment when making decisions."

  

23.  "Write a marketing campaign outline that avoids relying on stereotypes or typical examples when targeting \[ideal customer persona\]. Use the representativeness heuristic to consider the full range of information and avoid biases and errors in judgment. Use data and statistics to support the value of considering the full range of information."

  

25.  "Write a marketing campaign outline that takes into account the potential for psychological reactance among \[ideal customer persona\]. Highlight the autonomy and freedom that using the \[product/service\] provides, and avoid language or offers that may be perceived as controlling or restrictive. Emphasize the choice and control the audience has when using the product."

  

27.  "Write a marketing campaign outline that addresses the potential for the Dunning-Kruger Effect among \[ideal customer persona\]. Explain the importance of continuing education and learning about the \[product/service\] in order to make informed decisions. Use data and statistics to support the value of learning and to avoid overestimating one's own competence."

  

29.  "Please write a \[type of text\] outlining a marketing campaign that uses the availability heuristic to be aware of the importance of considering a wide range of information and not just relying on examples that are easily available or memorable. Identify any potential \[biases and errors in judgment\] that may occur due to the availability heuristic and create messaging and offers that consider a diverse range of examples and data points. Also, provide resources and support to help \[ideal customer persona\] consider a wide range of information when making a purchase decision."

  

31.  "Write a \[type of text\] outlining a marketing campaign that maps out the customer journey for \[ideal customer persona\] and creates tailored messaging and offers for each stage. Identify the \[touchpoints\] and \[emotional states\] that occur at each stage and create messaging and offers that align with these. Also, consider the role of \[customer feedback\] and how it can be used to improve the customer journey and increase conversion rates."

  

33.  "Please write a \[type of text\] outlining a marketing campaign using the diffusion of innovation model to predict and shape the adoption of \[product/service\] among \[ideal customer persona\]. Identify the \[early adopters\] and \[late majority\] within the target audience and create messaging and offers that appeal to their unique needs and motivations. Also, consider the role of \[opinion leaders\] and how they can help accelerate the diffusion process."

  

35.  "Write a \[type of text\] outlining a marketing campaign that uses the ladder of inference to better understand the thought processes of \[ideal customer persona\] and identify potential barriers to conversion. Consider the \[assumptions and beliefs\] that may influence their decision-making and create messaging and offers that address these. Also, provide resources and support to help them move through the ladder of inference and make a purchase decision."

  

37.  "Please write a \[type of text\] outlining a marketing campaign using the '80/20 Rule' (also known as the Pareto Principle) to identify and prioritize the most impactful areas for \[product/service\] growth. Identify the \[key metrics\] that contribute the most to \[desired outcome\] and create messaging and offers that focus on these areas. Also, consider the \[minority inputs\] that may have a disproportionate impact on the \[majority outputs\] and how to leverage these effectively."

# Psychological Frameworks

1.  "Write a marketing campaign outline using the 'Reciprocity Bias' framework to create a sense of obligation in \[ideal customer persona\] to try our \[product/service\]. Include value-adds or bonuses, and encourage reciprocity by asking for a favor or action in return."

  

3.  "Using the 'Attribution Bias' framework, please write a marketing campaign outline that attributes the successes or failures of our \[product/service\] to internal factors. Emphasize the internal qualities of our product and how it can help \[ideal customer persona\] achieve their goals."

  

5.  "Write a marketing campaign outline using the 'Anchoring Bias' framework to shape the perceptions of \[ideal customer persona\] about our \[product/service\]. Highlight the most important or relevant information first, and use this information as an anchor to influence their decisions."

  

7.  "Using the 'Self-Handicapping' framework, please write a marketing campaign outline that addresses potential obstacles or doubts \[ideal customer persona\] may have about using our \[product/service\]. Offer support and resources to help them overcome these challenges, and emphasize the internal qualities of our product that can help them achieve their goals."

  

9.  "Write a marketing campaign outline using the 'Confirmation Bias' framework to appeal to the \[ideal customer persona\]'s preexisting beliefs about \[subject\]. Present information in a way that supports their views and aligns with their values, and use \[persuasion technique\] to encourage them to take action and try our \[product/service\]."

  

11.  "Write a marketing campaign outline using the 'Self-Serve Bias' framework to highlight the successes people can achieve with our \[product/service\] and downplay the role of external factors in the outcomes. Explain how our product can help \[ideal customer persona\] reach their \[goal\] and present testimonials from satisfied customers."

  

13.  "Using the 'Social Comparison' framework, please write a marketing campaign outline that highlights the successes of others using our \[product/service\] and how it can help \[ideal customer persona\] achieve similar results. Present testimonials from satisfied customers and explain how our product can help them reach their \[goal\]."

  

15.  "Write a marketing campaign outline using the 'Social Learning' framework to showcase the successes and benefits of using our \[product/service\] for \[ideal customer persona\]. Describe the positive outcomes others have experienced with our product, and provide incentives for the reader to try it themselves."

  

17.  "Using the 'Self-Fulfilling Prophecy' framework, please write a marketing campaign outline that highlights the potential outcomes of using our \[product/service\] for \[ideal customer persona\]. Explain how our product can help them achieve their \[goal\] and present testimonials from satisfied customers to illustrate the positive impact it has had on others."

  

19.  "Using the 'Self-Efficacy' Theory, please write a marketing campaign outline that builds confidence in \[ideal customer persona\] and helps them feel capable of achieving their goals with our \[product/service\]. Highlight the successes of others using our product and provide resources and support to help them feel equipped to take action."

  

21.  "Write a marketing campaign outline using the 'Self-Perception' Theory to persuade \[ideal customer persona\] to adopt a specific attitude or belief about our \[product/service\]. Encourage them to take small actions that are consistent with the desired attitude or belief, and highlight how these actions can influence their self-perception and lead to positive outcomes."

  

23.  "Using the 'That's-Not-All' Effect, please write a marketing campaign outline that starts with a small request, such as signing up for a newsletter or taking a small action, and then follows up with a larger request, such as making a purchase or signing up for a trial. Emphasize the benefits and value of the larger request and how it can help \[ideal customer persona\] achieve their goals."

  

25.  "Write a marketing campaign outline using the 'Sunk Cost Fallacy' framework to persuade \[ideal customer persona\] to continue investing in our \[product/service\] by highlighting the resources they have already invested and how it would be a waste to not see the returns on that investment. Emphasize the potential losses and regrets of not taking action and how our product can help them recoup their investments."

  

27.  "Write a marketing campaign outline using the 'Scarcity Principle' to create a sense of urgency and desire for our \[product/service\] among \[ideal customer persona\]. Highlight the limited availability or exclusive nature of the product, and provide a clear call to action for customers to take advantage of the opportunity before it's too late."

  

29.  "Write a marketing campaign outline using the 'Reactance' framework to respect the autonomy of \[ideal customer persona\] and allow them to feel in control of their decision-making process. Identify potential threats to their freedom or autonomy and create messaging and offers that address these threats and maintain their sense of control."

  

31.  "Using the 'Loss Aversion' framework, please write a marketing campaign outline that emphasizes the potential losses that \[ideal customer persona\] may incur if they don't take action on our \[product/service\]. Identify the specific losses they may face and use this as a motivator to take action."

  

33.  "Write a marketing campaign outline using the 'Framing Effect' framework to present information about our \[product/service\] in a way that influences the perception and decision-making of \[ideal customer persona\]. Consider the different frames that could be used (e.g. gain vs loss, positive vs negative) and choose the most favorable frame for our product."

  

35.  "Using the 'Classical Conditioning' framework, please write a marketing campaign outline that associates our \[product/service\] with positive outcomes and reinforces this association through repetition. Identify the stimulus (our product) and the desired response (a positive action, such as a purchase), and create a plan for reinforcing this association."

  

37.  "Write a marketing campaign outline using the 'Anchoring and Adjustment' framework to influence the decision-making process of \[ideal customer persona\] by providing an initial reference point or offer. Use this anchor to guide the customer towards a desired outcome, taking into account the adjustments they may make based on this anchor."

  

39.  "Write a marketing campaign outline using the Attachment Theory to appeal to the emotional and psychological bonds of \[ideal customer persona\]. Identify the security and comfort they seek in close relationships and present our \[product/service\] as a way to enhance the quality of these relationships and improve their overall well-being. Include testimonials from happy customers and highlight the benefits of using our product in their relationships."

  

41.  "Write a marketing campaign using Cognitive Dissonance Theory to reduce any conflicting beliefs or actions of \[ideal customer persona\] and increase conversion rates. Highlight the benefits and value of using our \[product/service\] and how it aligns with their values and beliefs. Include testimonials and examples of others using the product successfully to reduce any potential dissonance."

  

43.  "Using Self-Determination Theory, create a marketing campaign that speaks to the \[autonomy\], \[competence\], and \[relatedness\] of \[ideal customer persona\]. Emphasize the control and choice they have in using our \[product/service\] and how it aligns with their values and goals. Provide examples and testimonials of others using the product successfully to build confidence and a sense of competence."

  

45.  "Write a marketing campaign using Social Identity Theory to appeal to the \[identity\] of \[ideal customer persona\]. Highlight the benefits of using our \[product/service\] and how it aligns with their social identity and values. Include testimonials and examples of others in their social group using the product successfully to create a sense of belonging and positivity."

  

47.  "Using Maslow's Hierarchy of Needs, create a marketing campaign that speaks to the \[current need\] of \[ideal customer persona\]. Highlight how our \[product/service\] can help them meet this need and move up the hierarchy towards self-actualization. Use language that resonates with their current stage in the hierarchy and addresses their specific needs and goals."

# Content Creation Frameworks

1.  "Using the 'Situation-Complication-Resolution' framework, please write a marketing campaign outline that presents a \[situation\] faced by \[ideal customer persona\], discusses the \[complication\] that arises from the situation, and presents our \[product/service\] as the \[resolution\] to the problem. End with a call to action that encourages the reader to take advantage of the solution."

  

3.  "Using the 'Emotional Value Proposition' framework, please write a marketing campaign outline that speaks to the \[emotional needs\] of \[ideal customer persona\] and presents our \[product/service\] as the solution that will fulfill those needs. Identify the \[desired emotion\], create a \[story\] that evokes that emotion, and include \[testimonials\] from customers who have experienced that emotion after using our product."

  

5.  "Write a marketing campaign outline using the 'Customer Journey Map' framework that visualizes the journey from \[awareness\] to \[conversion\] for \[ideal customer persona\] and creates content that aligns with each stage. Identify their \[pain points\] and present our \[product/service\] as a solution to those issues, highlighting the \[features\] and \[benefits\] of our product and explaining how it can \[improve their situation\]."

  

7.  "Using the 'Marketing Funnel' framework, please write a marketing campaign outline that targets \[awareness/consideration/conversion\] stage of the customer journey and aligns with the goals of each stage. Highlight the \[features\] of our \[product/service\] and explain how it can \[solve a problem\] or \[achieve a goal\] for \[ideal customer persona\]."

  

9.  "Write a marketing campaign outline using the 'Empathy Map' framework to understand the thoughts, feelings, and needs of \[ideal customer persona\]. Identify their pain points and create content that speaks to those issues, addressing their \[thoughts\], \[feelings\], and \[needs\] with our \[product/service\]."

  

11.  "Using the 'SCAMPER' framework, please write a marketing campaign outline that suggests creative ways to \[substitute/combine/adapt/modify/put to other uses/eliminate/rearrange\] our \[product/service\] in order to make it more appealing to \[ideal customer persona\]."

  

13.  Using the 'Product-Market Fit' framework, please write a marketing campaign outline that demonstrates how our \[product/service\] is a perfect fit for the needs and pain points of \[ideal customer persona\]. Identify the specific problems faced by the target market, explain how our product addresses these issues, and provide evidence or testimonials to back up our claims. Emphasize the benefits of using our product and how it can improve the reader's life or business."

  

15.  "Write a marketing campaign outline using the 'Storyboard' framework to outline the key elements of a \[story\] about our \[product/service\]. Include the \[protagonist\], \[conflict\], and \[resolution\] and use these elements to create a compelling narrative that resonates with \[ideal customer persona\]."

  

17.  "Using the 'Myth-Busting' framework, please write a marketing campaign outline that identifies and debunks common misconceptions or myths about our \[product/service\]. Provide \[facts\] and \[evidence\] to support your claims."

  

19.  "Write a marketing campaign outline using the 'Storytelling' framework to create a narrative around our \[product/service\]. Use \[characters\], \[plot\], and \[setting\] to engage \[ideal customer persona\] and build emotional connections."

  

21.  "Using the 'Case Study' framework, please write a marketing campaign outline that presents a real-life example of how our \[product/service\] has successfully solved a \[problem\] or achieved a \[goal\] for a specific \[customer\]. Include details on the \[challenges\] faced by the customer and how our product provided a \[solution\]."

  

23.  "Write a marketing campaign outline using the 'Question-Answer' framework to start with a \[question\] relevant to \[ideal customer persona\] and provide a thorough and informative answer. Explain the importance of the question and why it matters to the reader."

  

25.  "Using the 'Compare-Contrast' framework, please write a marketing campaign outline that compares and contrasts two or more options or ideas to help \[ideal customer persona\] make an informed decision. Explain the pros and cons of each option and provide examples to support your points."

  

27.  "Write a marketing campaign outline using the 'How-To' framework to provide step-by-step instructions on how to complete a specific \[task\] or achieve a particular \[goal\] for \[ideal customer persona\]. Include clear and concise steps and any necessary resources or tools."

  

29.  "Using the 'Problem-Solution' framework, please write a marketing campaign outline that identifies a \[problem\] faced by \[ideal customer persona\] and offers a solution through our \[product/service\]. Explain how our product can solve their problem and improve their situation."

  

31.  "Write a marketing campaign outline using the 'Scannable Content' framework to create content that is easy to scan and read quickly for \[ideal customer persona\]. Include clear headings, bullet points, and short paragraphs to make the content more accessible and effective."

  

33.  "Write a \[type of content\] using the Rule of One framework that focuses on one main \[idea\], one main \[message\], or one main \[call to action\] in order to make the content more effective and memorable."

  

35.  "Using the PESO Model, create a \[type of content\] that is \[paid\], \[earned\], \[shared\], or \[owned\] in order to reach a wider \[audience\] and increase \[engagement\]."

  

37.  "Write a \[type of content\] using the SPIN framework that uses specific, provocative, informative, and emotional \[language\] to create compelling content that persuades the reader to take \[action\]."

  

39.  "Create a \[type of content\] using the Inverted Pyramid framework that starts with the most important \[information\] and then moves on to less important \[details\], so that readers can quickly get the main points."

  

41.  "Write a \[type of content\] using the Hero's Journey framework that follows the journey of a \[hero\] from \[ordinary\] to \[extraordinary\] through \[challenges\] and \[obstacles\], ultimately achieving their \[goal\]."

# Copywriting Frameworks

1.  "Using the 'Emotional Appeal' framework, please write a marketing campaign outline that uses \[emotional appeal\] to persuade \[ideal customer persona\] to take action and purchase our \[product/service\]. Choose an emotion such as \[fear\], \[happiness\], or \[guilt\]."

  

3.  "Write a marketing campaign outline using the 'Social Proof' framework to demonstrate the value and effectiveness of our \[product/service\] to \[ideal customer persona\]. Include \[testimonials\], \[case studies\], and \[industry experts\] as social proof."

  

5.  "Using the 'Empathy' framework, please write a marketing campaign outline that identifies the \[needs\] and \[pain points\] of \[ideal customer persona\] and crafts copy that demonstrates understanding and empathy for their situation. Present our \[product/service\] as a solution to their problems."

  

7.  "Write a marketing campaign outline using the 'Future Pacing' framework to help \[ideal customer persona\] visualize a future where they have achieved their \[goals\] with the help of our \[product/service\]. Describe the \[benefits\] they will receive as a result."

  

9.  "Using the 'Benefits-Features-Proof' framework, please write a marketing campaign outline that outlines the \[benefits\] our \[product/service\] provides to \[ideal customer persona\]. Explain the \[features\] that make these benefits possible and provide \[proof\] to back up our claims about the product."

  

11.  "Using the 'Unique Value Proposition' framework, please write a marketing campaign outline that identifies the unique value our \[product/service\] provides to \[ideal customer persona\] and crafts copy that clearly communicates that value."

  

13.  "Write a marketing campaign outline using the 'Attention-Interest-Desire-Action' framework to grab the attention of \[ideal customer persona\] and persuade them to take action. Start with a bold statement to get their attention, present information that piques their \[interest\], state the benefits of our \[product/service\] to create \[desire\], and ask for a sign-up or purchase."

  

15.  "Using the 'PASTOR' framework, write a marketing campaign outline that addresses the pain points of \[ideal customer persona\] and presents our \[product/service\] as the solution. Identify the \[problem\] they are facing, amplify the consequences of not solving it, tell a \[story\] related to the problem, include \[testimonials\] from happy customers, present our \[offer\], and request a response."

  

17.  "Write a marketing campaign outline using the 'Features-Advantages-Benefits' framework that highlights the \[features\] of our \[product/service\] and explains how these \[advantages\] can be helpful to \[ideal customer persona\]. Outline the \[benefits\] of our product and how it can positively impact the reader."

  

19.  "Using the 'Awareness-Comprehension-Conviction-Action' framework, please write a marketing campaign outline that presents \[ideal customer persona\] with a \[situation or problem\] and helps them understand it. Create the desired conviction in the reader to use our \[product/service\] as the solution and prompt the reader to take action."

  

21.  "Write a marketing campaign outline using the 'Star-Story-Solution' framework to introduce the main character of a \[story\] related to our \[product/service\] and keep the reader hooked. End the story with an explanation of how the star wins in the end with the help of our product."

  

23.  "Using the 'Picture-Promise-Prove-Push' framework, please write a marketing campaign outline that paints a picture that gets the attention and creates desire for our \[product/service\] in \[ideal customer persona\]. Describe how our product will deliver on its promises, provide testimonials to back up those promises, and give a little push to encourage the reader to take action."

  

25.  "Write a marketing campaign outline using the 'Problem-Agitate-Solve' framework to identify the most painful \[problem\] faced by \[ideal customer persona\] and agitate the issue to show why it is a bad situation. Present our \[product/service\] as the logical solution to the problem."

  

27.  "Using the 'Before-After-Bridge' framework, please write a marketing campaign outline that presents the current situation with a \[problem\] faced by \[ideal customer persona\]. Show them the world after using our \[product/service\] and how it has improved their situation. Then, provide a \[bridge\] to show them how they can get to that improved state by using our product."

  

29.  "Write a marketing campaign outline using the 'Unique Selling Proposition' framework to highlight the \[unique selling points\] of our \[product/service\] to \[ideal customer persona\]. Craft copy that clearly communicates these points and persuades the reader to take action."

  

31.  "Write a marketing campaign outline using the 'Headline' framework to identify the main benefit or value proposition of our \[product/service\] and craft a headline that clearly communicates that benefit to \[ideal customer persona\]."

  

33.  "Write a marketing campaign outline using the 'Hook-Story-Offer' framework to use a hook or attention-grabber to engage \[ideal customer persona\], tell a story to create an emotional connection, and then present an offer or call to action."

  

35.  "Using the 'CAB' formula, write a marketing campaign outline that highlights the features of our \[product/service\], explains the advantages of those features, and then outlines the benefits that \[ideal customer persona\] will receive as a result."

  

37.  "Write a marketing campaign outline using the 'PAS' formula to identify the problem faced by \[ideal customer persona\], agitate that problem to make it more pressing, and then present our \[product/service\] as the solution."

  

39.  "Using the 'AIDA' formula, write a marketing campaign outline to capture the attention of \[ideal customer persona\], create interest in our \[product/service\], generate desire for it, and ultimately prompt them to take action."

# Growth Hacking Frameworks

1.  "Write a marketing campaign outline using the 'Lean UX Cycle' framework to identify user needs for our \[product/service\] and rapidly prototype and test design solutions to meet those needs. Describe the steps you would take to iterate based on user feedback and include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

3.  "Using the 'Job-to-be-Done' framework, please write a marketing campaign outline that identifies the specific 'job' that customers are trying to do with our \[product/service\] and describes how we can design products and services that help them get it done more effectively. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

5.  "Write a marketing campaign outline using the 'Funnel Framework' to identify the key stages of the customer journey for our \[product/service\] and create a tailored marketing and sales strategy to move customers through each stage. Describe the specific tactics and channels you would use at each stage and include specific metrics you would use to measure the effectiveness of this approach."

  

7.  "Using the 'Growth Scaling Framework,' please write a marketing campaign outline that identifies the key drivers of growth for our \[product/service\] and sets clear goals and metrics to measure progress. Describe how you would implement a scalable growth strategy and include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

9.  "Write a marketing campaign outline using the 'Marketing Hourglass' framework to identify the most valuable customer segments for our \[product/service\] and create a tailored marketing strategy to reach and engage them. Describe the specific tactics and channels you would use to reach and engage these customers and include specific metrics you would use to measure the effectiveness of this approach."

  

11.  "Using the 'Growth Hacking Playbook' framework, please write a marketing campaign outline that outlines a systematic approach to identifying, testing, and scaling growth opportunities for our \[product/service\]. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

13.  "Write a marketing campaign outline using the 'Growth Marketing Framework' to identify and prioritize growth opportunities for our \[product/service\] and set clear goals and metrics to measure progress. Describe how you would implement a data-driven, iterative marketing strategy to drive growth and include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

15.  "Using the 'Customer Development Process' framework, please write a marketing campaign outline that identifies and validates customer needs for our \[product/service\] and describes how you would build and test prototypes to meet those needs. Outline the steps you would take to iterate based on customer feedback and include specific tactics and metrics you would use to measure success."

  

17.  "Write a marketing campaign outline using the 'Growth Team Framework' to build a cross-functional team with the skills and expertise needed to drive growth for our \[product/service\] and describe how you would establish clear roles, responsibilities, and processes to support it. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

19.  "Using the 'Growth Stack' framework, please write a marketing campaign outline that identifies and prioritizes the key tools and technologies needed to drive growth for our \[product/service\] and describes how you would implement them. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

21.  "Write a marketing campaign outline using the 'Four Steps to the Epiphany' framework to outline the key steps involved in launching a successful startup for our \[product/service\], including identifying a compelling value proposition, building a minimal viable product, and driving customer acquisition. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

23.  "Using the 'Innovation Matrix' framework, please write a marketing campaign outline that identifies areas of our business where incremental or disruptive innovation can drive growth and describe how you would implement these ideas. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

25.  "Write a marketing campaign outline using the 'Growth Mindset Framework' to emphasize the importance of a growth mindset and describe how you would encourage our team to embrace a culture of continuous learning and experimentation. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

27.  "Using the 'Growth Pyramid' framework, please write a marketing campaign outline that identifies the core elements of a successful growth strategy for our \[product/service\] and describes how we will build upon them to drive growth. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

29.  "Write a marketing campaign outline using the 'Lean Analytics Cycle' framework to identify a specific problem or opportunity for our \[product/service\] and describe how you would measure and analyze data to understand it. Outline the steps you would take to iterate and experiment to find a solution and include specific tactics and metrics you would use to measure success."

  

31.  "Using the 'Bullseye Framework,' please write a marketing campaign outline that involves identifying the most valuable customer segments for our \[product/service\] and the key channels through which to reach them. Describe the highest impact growth levers you would pull to drive growth and include specific tactics and metrics you would use to measure success."

  

33.  "Write a marketing campaign outline using the 'Growth Hacking Canvas' framework to identify and prioritize growth opportunities for our \[product/service\] by mapping out the key elements of our product, market, and customer segments. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

35.  "Using the 'Growth Flywheel' framework, please write a marketing campaign outline that describes how we can achieve growth through a continuous feedback loop involving the acquisition of customers, retention and engagement, and using customer insights to improve our \[product/service\]. Include specific tactics and metrics you would use to measure the effectiveness of this approach."

  

37.  "Write a marketing campaign outline using the 'AARRR (Pirate Metrics)' framework to outline the key stages of the customer journey for our \[product/service\] and describe how we will acquire, activate, retain, refer, and generate revenue from \[ideal customer persona\]. Include specific tactics and metrics you would use to measure success at each stage."

  

39.  "Using the 'Lean Startup Methodology' framework, please outline a marketing campaign that involves rapid experimentation and iteration to find a scalable business model for our \[product/service\] that will appeal to \[ideal customer persona\]. Describe the steps you would take to validate your assumptions and gather feedback from customers to inform your marketing strategy."

# Music

1.  I want you to act as a composer. I will provide the lyrics to a song and you will create music for it. This could include using various instruments or tools, such as synthesizers or samplers, in order to create melodies and harmonies that bring the lyrics to life. My first request is "I have written a poem named “Hayalet Sevgilim” and need music to go with it."

  

3.  I want you to act as a rapper. You will come up with powerful and meaningful lyrics, beats and rhythm that can ‘wow’ the audience. Your lyrics should have an intriguing meaning and message which people can relate too. When it comes to choosing your beat, make sure it is catchy yet relevant to your words, so that when combined they make an explosion of sound everytime! My first request is "I need a rap song about finding strength within yourself."

  

5.  I want you to act as a composer. I will provide the lyrics to a song and you will create music for it. This could include using various instruments or tools, such as synthesizers or samplers, in order to create melodies and harmonies that bring the lyrics to life. My first request is "I have written a poem named “Hayalet Sevgilim” and need music to go with it."

# Health

1.  I want you to act as a motivational coach. I will provide you with some information about someone's goals and challenges, and it will be your job to come up with strategies that can help this person achieve their goals. This could involve providing positive affirmations, giving helpful advice or suggesting activities they can do to reach their end goal. My first request is "I need help motivating myself to stay disciplined while studying for an upcoming exam".

  

3.  I want you to act as a relationship coach. I will provide some details about the two people involved in a conflict, and it will be your job to come up with suggestions on how they can work through the issues that are separating them. This could include advice on communication techniques or different strategies for improving their understanding of one another's perspectives. My first request is "I need help solving conflicts between my spouse and myself."

  

5.  I want you to act as a motivational speaker. Put together words that inspire action and make people feel empowered to do something beyond their abilities. You can talk about any topics but the aim is to make sure what you say resonates with your audience, giving them an incentive to work on their goals and strive for better possibilities. My first request is "I need a speech about how everyone should never give up."

  

7.  I want you to act as a life coach. I will provide some details about my current situation and goals, and it will be your job to come up with strategies that can help me make better decisions and reach those objectives. This could involve offering advice on various topics, such as creating plans for achieving success or dealing with difficult emotions. My first request is "I need help developing healthier habits for managing stress."

  

9.  I want you to act as a pet behaviorist. I will provide you with a pet and their owner and your goal is to help the owner understand why their pet has been exhibiting certain behavior, and come up with strategies for helping the pet adjust accordingly. You should use your knowledge of animal psychology and behavior modification techniques to create an effective plan that both the owners can follow in order to achieve positive results. My first request is "I have an aggressive German Shepherd who needs help managing its aggression."

  

11.  I want you to act as a personal trainer. I will provide you with all the information needed about an individual looking to become fitter, stronger and healthier through physical training, and your role is to devise the best plan for that person depending on their current fitness level, goals and lifestyle habits. You should use your knowledge of exercise science, nutrition advice, and other relevant factors in order to create a plan suitable for them. My first request is "I need help designing an exercise program for someone who wants to lose weight."

  

13.  I want you to act as a mental health adviser. I will provide you with an individual looking for guidance and advice on managing their emotions, stress, anxiety and other mental health issues. You should use your knowledge of cognitive behavioral therapy, meditation techniques, mindfulness practices, and other therapeutic methods in order to create strategies that the individual can implement in order to improve their overall wellbeing. My first request is "I need someone who can help me manage my depression symptoms."

  

15.  I want you to act as a mental health adviser. I will provide you with an individual looking for guidance and advice on managing their emotions, stress, anxiety and other mental health issues. You should use your knowledge of cognitive behavioral therapy, meditation techniques, mindfulness practices, and other therapeutic methods in order to create strategies that the individual can implement in order to improve their overall wellbeing. My first request is "I need someone who can help me manage my depression symptoms."

  

17.  I want you to act as a dentist. I will provide you with details on an individual looking for dental services such as x-rays, cleanings, and other treatments. Your role is to diagnose any potential issues they may have and suggest the best course of action depending on their condition. You should also educate them about how to properly brush and floss their teeth, as well as other methods of oral care that can help keep their teeth healthy in between visits. My first request is "I need help addressing my sensitivity to cold foods."

  

19.  I want you to act as a doctor and come up with creative treatments for illnesses or diseases. You should be able to recommend conventional medicines, herbal remedies and other natural alternatives. You will also need to consider the patient’s age, lifestyle and medical history when providing your recommendations. My first suggestion request is “Come up with a treatment plan that focuses on holistic healing methods for an elderly patient suffering from arthritis".

  

21.  As a dietitian, I would like to design a vegetarian recipe for 2 people that has approximate 500 calories per serving and has a low glycemic index. Can you please provide a suggestion?

# Fun

1.  Act as a drunk person
    1.  Let's play a game. You will role play as if you were drunk. Make your answer's incoherent.
2.  Act as a character from a movie or a book or anything
    1.  I want you to act like {Character} from {series}. I want you to respond and answer like {Character}. do not write any explanations. only answer like {character}. You must know all of the knowledge of {character}. My first sentence is "Hi Character"
3.  Stand-up comedian
    1.  I want you to act as a stand-up comedian. I will provide you with some topics related to current events and you will use your wit, creativity, and observational skills to create a routine based on those topics. You should also be sure to incorporate personal anecdotes or experiences into the routine in order to make it more relatable and engaging for the audience. My first request is "I want an humorous take on politics."
4.  Magician
    1.  I want you to act as a magician. I will provide you with an audience and some suggestions for tricks that can be performed. Your goal is to perform these tricks in the most entertaining way possible, using your skills of deception and misdirection to amaze and astound the spectators. My first request is "I want you to make my watch disappear! How can you do that?"
5.  Fancy Title Generator
    1.  I want you to act as a fancy title generator. I will type keywords via comma and you will reply with fancy titles. my first keywords are api,test,automation
6.  Midjourney prompt generator
    1.  I want you to act as a prompt generator for Midjourney's artificial intelligence program. Your job is to provide detailed and creative descriptions that will inspire unique and interesting images from the AI. Keep in mind that the AI is capable of understanding a wide range of language and can interpret abstract concepts, so feel free to be as imaginative and descriptive as possible. For example, you could describe a scene from a futuristic city, or a surreal landscape filled with strange creatures. The more detailed and imaginative your description, the more interesting the resulting image will be. Here is your first prompt: "A field of wildflowers stretches out as far as the eye can see, each one a different color and shape. In the distance, a massive tree towers over the landscape, its branches reaching up to the sky like tentacles."
7.  Prompt Generator
    1.  I want you to act as a prompt generator. Firstly, I will give you a title like this: "Act as an English Pronunciation Helper". Then you give me a prompt like this: "I want you to act as an English pronunciation assistant for Turkish speaking people. I will write your sentences, and you will only answer their pronunciations, and nothing else. The replies must not be translations of my sentences but only pronunciations. Pronunciations should use Turkish Latin letters for phonetics. Do not write explanations on replies. My first sentence is "how the weather is in Istanbul?"." (You should adapt the sample prompt according to the title I gave. The prompt should be self-explanatory and appropriate to the title, don't refer to the example I gave you.). My first title is "Act as a Code Review Helper" (Give me prompt only)
8.  Lunatic
    1.  I want you to act as a lunatic. The lunatic's sentences are meaningless. The words used by lunatic are completely arbitrary. The lunatic does not make logical sentences in any way. My first suggestion request is "I need help creating lunatic sentences for my new series called Hot Skull, so write 10 sentences for me".
9.  Time Travel Guide
    1.  I want you to act as my time travel guide. I will provide you with the historical period or future time I want to visit and you will suggest the best events, sights, or people to experience. Do not write explanations, simply provide the suggestions and any necessary information. My first request is "I want to visit the Renaissance period, can you suggest some interesting events, sights, or people for me to experience?"
10.  Emoji Translator
    1.  I want you to translate the sentences I wrote into emojis. I will write the sentence, and you will express it with emojis. I just want you to express it with emojis. I don't want you to reply with anything but emoji. When I need to tell you something in English, I will do it by wrapping it in curly brackets like {like this}. My first sentence is "Hello, what is your profession?"
