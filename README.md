# Online_Quiz
In a variety of education settings, personalized feedback greatly enhances the learning experience. Intelligent Tutoring Systems provide real-time feedback, but they typically rely on the student to self diagnose the need for help, which may cause an under- or overuse of hints. Consequently, we examined how changing the availability of hints affects their use. In order to do this, we developed an online, multiple choice quiz with five mathematical logic problems. Each problem has two, increasingly specific hints available, and hints are made available through one of various different hint design strategies. We evaluated how feedback availability affects the count, frequency, and timing of its use.  

hint1.php has code for hint design type 1 - Making hints available to the user all the time and it is up to the user to access them. Hint 2 can be accessed after using Hint 1.    

hint2.php has code for hint design type 2 - Making hints available when problem solving time exceeds some predetermined time.   Hint 1 will be available thus after problem solving time exceeds some preset time. Hint 2 will be available after some time when user accesses Hint 1.    

hint 3.php has code for hint design type 3 - Making only a limited number of hints available to the user. Afer the user uses up all the provided hints, he cannot access any more of them.

hint1_demo.html, hint2_demo.html, hint3_demo.html are INTERACTIVE demo (instruction) pages providing a brief tour of the online quiz with the respective hint design type.      

This app is hosted online on a vps and a link is given to access the app. When server receives an incoming request, it radomly assigns one of the available variants to the user and evenly distributes available variants among all incoming requests. User will be taking our quiz, after going through the tutorial (demo) section.     
