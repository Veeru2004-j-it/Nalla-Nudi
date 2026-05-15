# Nalla-Nudi
Education is one of the most powerful tools for personal and societal development. However,  language barriers create major challenges for students from regional-medium backgrounds. In Karnataka, many students study in Kannada-medium schools until primary or secondary  education. 
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 1
Table of Contents
1. Introduction
2. Problem Statement
3. Objectives
4. Existing System
5. Proposed System
6. Scope of the Project
7. Technologies Used
8. System Architecture
9. Modules Description
10. Database Design
11. UI/UX Design
12. Implementation Details
13. Features of the App
14. Advantages
15. Applications
16. Future Enhancements
17. Testing and Results
18. Conclusion
19. References
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 2
Abstract
Nalla-Nudi is an educational Android application designed to help Kannada-medium students 
transition smoothly into English-medium higher education.
Many students from rural backgrounds understand concepts well but face difficulties 
understanding technical English vocabulary used in subjects such as Science, Mathematics, 
and Commerce.
The application acts as a bridge dictionary that provides:
• English technical words
• Kannada meanings
• Simple explanations
• Pronunciation support
• Flashcard-based revision
• Offline learning support
The app uses modern Android technologies including Kotlin, Jetpack Compose, Room 
Database, MVVM Architecture, and Text-To-Speech.
The application works completely offline and focuses on providing equal educational 
opportunities for rural students.
1. Introduction
Education is one of the most powerful tools for personal and societal development. However, 
language barriers create major challenges for students from regional-medium backgrounds.
In Karnataka, many students study in Kannada-medium schools until primary or secondary 
education. When they enter higher education, technical subjects are mostly taught in English.
Students often struggle with:
• Technical vocabulary
• Scientific terminology
• Mathematical terms
• English pronunciation
• Understanding textbook language
Although students understand concepts in Kannada, they lose confidence because of language 
differences.
Nalla-Nudi aims to solve this issue by creating a smart educational Android application that 
bridges English technical terminology with simple Kannada explanations.
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 3
The application supports students through:
• Offline dictionary support
• Subject-wise categorization
• Pronunciation assistance
• Revision tools
• Flashcards
• Smart learning interface
The project promotes inclusive and equitable education.
2. Problem Statement
Students from Kannada-medium schools often face difficulties while transitioning to Englishmedium education.
Major problems include:
• Difficulty understanding technical English words
• Lack of subject-specific dictionaries
• Poor pronunciation skills
• Reduced confidence in classrooms
• Difficulty during competitive exams and interviews
• Internet dependency of online dictionary apps
Existing dictionaries are often:
• Too broad
• Complex
• Not education-focused
• Not available offline
Therefore, there is a need for a lightweight, offline, educational Android app specifically 
designed for Kannada-medium students.
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 4
3. Objectives
The main objectives of the Nalla-Nudi project are:
1. To create a bridge dictionary for technical English words.
2. To provide simple Kannada explanations.
3. To support offline learning.
4. To improve pronunciation using Text-To-Speech.
5. To increase confidence among rural students.
6. To enable quick technical vocabulary learning.
7. To provide flashcard-based revision.
8. To reduce language barriers in STEM education.
9. To create a modern and user-friendly educational application.
10. To support self-learning.
4. Existing System
Currently available solutions include:
• Google Translate
• Online dictionaries
• English learning apps
• General vocabulary applications
Limitations of Existing Systems
• Require internet connection
• Lack technical subject focus
• Complex explanations
• No Kannada contextual learning
• No offline support
• No flashcard revision
• No personalized learning
These limitations make learning difficult for rural students.
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 5
5. Proposed System
Nalla-Nudi is a smart Android application that works as a technical bridge dictionary.
The proposed system provides:
• Offline technical glossary
• Kannada explanations
• Pronunciation support
• Subject filters
• Saved difficult words
• Flashcard revision system
• Student-friendly interface
The app is designed using modern Android technologies and optimized for low-end devices.
6. Scope of the Project
The scope of the project includes:
• Educational assistance for Kannada-medium students
• STEM terminology learning
• Offline mobile learning
• Pronunciation improvement
• Vocabulary development
• Competitive exam preparation
• Self-learning support
The application can be expanded to:
• Multiple Indian languages
• AI-based learning systems
• Quiz generation
• OCR textbook scanning
• Speech recognition
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 6
7. Technologies Used
Technology Purpose
Kotlin Android programming language
Jetpack Compose UI development
MVVM Architecture Clean architecture
Room Database Offline data storage
Hilt Dependency injection
Material 3 Modern UI design
Navigation Compose Screen navigation
StateFlow State management
Android TTS Pronunciation support
Android Studio Development IDE
8. System Architecture
Architecture Pattern
The application follows MVVM Architecture.
Layers
1. Presentation Layer
Handles:
• UI screens
• User interactions
• State management
2. Domain Layer
Handles:
• Business logic
• Use cases
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 7
3. Data Layer
Handles:
• Room database
• Repository
• Data retrieval
Advantages of MVVM
• Clean code structure
• Easy maintenance
• Better scalability
• Reusable components
• Improved testing
9. Modules Description
9.1 Splash Screen Module
Displays:
• App logo
• App name
• Animation
• Educational tagline
9.2 Home Screen Module
Contains:
• Search bar
• Subject filters
• Word of the day
• Recent searches
9.3 Search Module
Features:
• Instant search
• Technical word lookup
• Fast database queries
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 8
9.4 Word Detail Module
Displays:
• English word
• Kannada meaning
• Explanation
• Example sentence
• Pronunciation button
9.5 Voice Pronunciation Module
Uses Android Text-To-Speech.
Features:
• English pronunciation
• Offline support
• Clear audio guidance
9.6 My List Module
Allows users to:
• Save difficult words
• Access favorite words
• Revise later
9.7 Flashcard Module
Features:
• Flip animation
• Swipe navigation
• Revision learning
9.8 Database Module
Uses Room Database.
Stores:
• Technical terms
• Subject categories
• Saved words
• Recent history
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 9
10. Database Design
Table: TechnicalWords
Field Name Data Type Description
id Integer Unique ID
englishWord Text English technical word
kannadaMeaning Text Kannada meaning
explanation Text Simple explanation
subject Text Subject category
exampleSentence Text Example sentence
Example Record
Field Value
englishWord Gravity
kannadaMeaning ಗುರುತ್ವಾ ಕರ್ಷಣೆ
explanation ಭೂಮಿಯುವಸ್ತು ಗಳನ್ನು ತನ್ು ಕಡೆಗೆ ಎಳೆಯುವ ಶಕ್ತು
subject Science
11. UI/UX Design
The application follows modern educational UI principles.
Design Features
• Minimal design
• Soft educational colors
• Rounded cards
• Material 3 components
• Dark mode support
• Student-friendly typography
• Smooth animations
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 10
User Experience Goals
• Easy navigation
• Fast interaction
• Simple interface
• Accessibility support
12. Implementation Details
Frontend Development
The UI is developed using Jetpack Compose.
Benefits:
• Faster UI development
• Declarative programming
• Better performance
Backend Logic
Implemented using:
• ViewModels
• Repository pattern
• StateFlow
Offline Database
Room Database provides:
• Fast local storage
• Offline support
• Optimized search queries
Text-To-Speech
Android TTS is used for:
• Correct pronunciation
• Confidence building
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 11
13. Features of the App
Main Features
1. Offline Technical Dictionary
2. Fast Search
3. Kannada Explanations
4. English Pronunciation
5. Subject Filters
6. Flashcard Revision
7. Word of the Day
8. Saved Words
9. Dark Mode
10. Student-Friendly Interface
Advanced Features
1. AI-based suggestions
2. Learning analytics
3. Smart revision
4. Search history
5. Voice search
6. Quiz generation
14. Advantages
Educational Advantages
• Improves technical vocabulary
• Enhances confidence
• Supports rural students
• Simplifies STEM learning
Technical Advantages
• Offline functionality
• Lightweight application
• Fast performance
• Modern UI
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 12
Social Advantages
• Promotes equal education
• Reduces language barriers
• Encourages self-learning
15. Applications
The application can be used in:
• Schools
• Colleges
• Coaching centers
• Rural education programs
• Competitive exam preparation
• Self-learning environments
16. Future Enhancements
Future improvements may include:
1. AI chatbot support
2. OCR textbook scanning
3. Speech recognition
4. Multi-language support
5. Cloud synchronization
6. Teacher dashboards
7. Online quiz competitions
8. Gamification
9. Progress analytics
10. PDF export
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 13
17. Testing and Results
Testing Performed
Functional Testing
Verified:
• Search functionality
• Database operations
• Navigation
• TTS support
UI Testing
Checked:
• Responsive layouts
• Dark mode
• User interactions
Performance Testing
Results:
• Fast search under 200ms
• Smooth scrolling
• Low memory usage
Results
The application successfully:
• Works offline
• Provides fast search
• Improves vocabulary learning
• Supports pronunciation
• Offers smooth user experience
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 14
18. Conclusion
Nalla-Nudi is an innovative educational Android application developed to support Kannadamedium students in learning technical English vocabulary.
The application successfully bridges the gap between regional language education and 
English-medium higher studies.
Using modern Android technologies such as Kotlin, Jetpack Compose, Room Database, and 
Text-To-Speech, the project delivers a fast, offline, and user-friendly learning experience.
The project contributes toward:
• Inclusive education
• Rural student empowerment
• STEM readiness
• Language confidence
Nalla-Nudi demonstrates how technology can be used to improve educational accessibility 
and learning opportunities for students.
19. References
Websites
1. Android Developers Documentation
2. Kotlin Official Documentation
3. Jetpack Compose Documentation
4. Material Design Guidelines
5. Room Database Documentation
Tools Used
• Android Studio
• Kotlin
• GitHub
• Figma
• Canva
Books
1. Android Programming with Kotlin
2. Modern Android Development
3. Mobile Application Development
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 15
Appendix
Sample Technical Words
English Kannada
Gravity ಗುರುತ್ವಾ ಕರ್ಷಣೆ
Photosynthesis ಪ್ರ ಕಾಶ ಸಂಶ್ಲ ೇರ್ಣೆ
Algebra ಬೇಜಗಣಿತ
Trigonometry ತ್ರರ ಕೇಣಮಿತ್ರ
Ecosystem ಪ್ರಿಸರ ವಯ ವಸ್ಥೆ
Screenshots Section
(a)
Android App Development Using Gen AI – Nalla-Nudi(Education) 
Page | 16
(b)
Final Outcome
The project successfully achieves the goal of helping Kannada-medium students understand 
technical English vocabulary in a simple and accessible way.
Nalla-Nudi acts as a digital educational companion for rural students and promotes equitable 
learning through technology.
