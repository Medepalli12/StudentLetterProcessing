**Introduction**

In the rapidly evolving landscape of technology, the ability to create dynamic and efficient console applications is a prized skill. The project is a console application using .NET Framework and C#. This report encapsulates the essence of our project, providing you with insights and how the project was developed.

Central to this project is to create a folder structure with CombinedLetters as the main folder which consists of two other sub-folders: Admission and Scholarship folders in it each folder contains a date folder in” YYYYMMDD” format and in that date folder, we have letters for both “Admission” and ‘’Scholarship” as admission-########.txt, scholarship-########.txt here the 8 digit code, the first four-digit are student id and second four digits are university id. These student’s university IDs are used to combine two letters and once the process is complete they move the files to the output folder and archive folder and generate a text report in the Output folder having the report of total combined text letters in it.

**Project Development Process**

The journey of creating this console application was a systematic and iterative process that involved multiple stages. The initial phase encompassed requirements gathering and conceptualization. The project scope was defined, and the key functionalities were identified, including the ability to create the basic folder structure based on the requirements. This phase was critical in establishing a clear roadmap for the project's development.

.NET and C# were employed to bring the project to life. First created the folder structure as per the requirements and check the text files in the date folder which resides in the Input if the student has both admission and Scholarship letters on the same day an interface is created for both Admission and Scholarship folders and checked the text file name which including the university ID in it and used that ID to check which student have both letters on the same day. If the text file name University ID matches in both Admission and Scholarship folders, then the two text files in the Input folder will move to the Output folder/Archive folder if it does not match the text file names then the folders will remain in the Input folder. In the Output folder, it saves the file with its University ID and will generate a text report file for a text file.

**User Interface**

The user interface of our application presents a console application. It has interactive elements which include text files to interact with the other folders with its unique Id, allowing users to effortlessly manage data. Each text file corresponds directly to a specific department within the organization, ensuring a direct connection between user applications.

**Exception Handling**

used exception handlers in C# to get the error and handle it while the console app is running and show the error message in the application.

**Technology Stack**

The project controls a potent technology stack to bring its functionalities to life. .NET serves as the foundational framework, enabling seamless console application development. C#, a versatile programming language, interacts seamlessly with .NET, facilitating dynamic and responsive console apps. 

**Lessons Learned**

A significant challenge was moving the text files from one folder to another. As the application's user base grew, the efficiency of moving the text files became difficult. Techniques such as using different IDs for the files explored enhance the application's responsiveness, highlighting the importance of scalability and performance tuning.

After moving the text files from the Input folder to the Output folder as per the requirements as it matches the student’s university Id’s unique identifiers for combining letters into one file, I don’t have any requirements on how to save when a student has admission file but don’t have the scholarship file. So, I have decided to save the text file based on students’ university IDs and move that file to the Output folder and generate the text report with that unique student’s university IDs with a count of how combined letters are generated in the Output folder.

**Discussion/ Testing the Application**

Project's foundation lies in the integration of .NET and C#, enabling the creation of a robust console application. The centerpiece of this application is its ability to manage interfaces seamlessly, highlighting the practical importance of folder structure throughout the application process.

An important aspect of this project is to maintain the folders structure in the console app, meticulously crafted to enhance user experience. The arrangement of elements such as folders and the files in them makes moving or merging files effortless. Furthermore, the implementation of text report operations empowers users with a comprehensive toolkit to manage files dynamically, ensuring data integrity and real-time content management.

While the project's progression was marked by significant achievements, it also encountered challenges intrinsic to the console application. Overcoming these challenges necessitated a strategic and adaptive approach, underscoring the iterative nature of software creation. The discussion underscores the insights gained from these experiences, illustrating the importance of problem-solving and adaptability in the development process.

**Step 1:**

**Create folder structure as per requirements as below:**
![CombinedLetters](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/d8fcc045-9aff-48f8-9c02-a65aafde09cb)

![Input](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/2876ca51-ba78-4e30-8498-c48057945a87)

![Input-Admission](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/bd9d16cf-d7a1-430a-8995-5df57452c960)

![Input-Scholarship](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/4ba1a2e0-f6db-4c1c-af5d-8402b4180ce9)

![Output](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/49ec468a-4d16-4a50-abd0-16a60ae1ad26)

**Step 2: Schedule the application to run daily at 10 AM on weekdays only.**
 
![image](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/8610066a-51fb-4b9d-9f7b-9af365513bf0)

![image](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/4754b2da-db0a-4eed-a92b-2006f1a7ccd9)

![image](https://github.com/Medepalli12/StudentLetterProcessing/assets/134563904/6ee1c7c3-d200-452c-b265-906a59f792ed)

**Conclusion:**

The mastery acquired in implementing the triad of collecting the data and moving the data with unique identifiers and merging the data in the application upon a sturdy foundation for future undertakings. The outcome of this project extends beyond its immediate scope, with the knowledge to create console projects which will position you at the front line of success in the Software development industry's forever evolving field. 
