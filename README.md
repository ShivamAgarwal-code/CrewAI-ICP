# CrewAI-ICP

## Inspiration
Our journey began with a simple yet profound goal: to revolutionize the grading system by eliminating bias and significantly easing the workload of educators. The idea struck us when we noticed the inconsistency and subjectivity in traditional grading methods. We aimed to create a solution that not only streamlines the grading process but also ensures fairness and objectivity in evaluating students' performances.

## What it does
Our application leverages AI to automatically grade tests. Teachers upload a PDF of the test, and our system generates a detailed rubric with specific criteria and point values for each question. Teachers are able to edit this rubric as they wish. Then, teachers can upload an image of a student's answers, and evauluAI grades each answer based on the predefined rubric, ensuring a consistent and unbiased grading process. This approach not only speeds up the grading process but also provides students with clear, constructive feedback based on objective criteria.

## How we built it
We built our application using React, Node.js, JavaScript, Firebase, Vercel/Next.js, and the OpenAI API. We deployed it on Vercel and we also deployed it separately using Motoko on the ICP platform. The frontend, developed with React, offers a user-friendly interface for uploading tests and viewing grades. On the backend, our serverless functions handle the processing of uploaded PDFs and images, converting them into a format that our AI can analyze. By integrating the OpenAI API, we leverage cutting-edge language models to interpret the test content and student answers, generating accurate and fair grades based on the criteria outlined in the rubric.

## Challenges we ran into
Deploying on the Internet Computer Protocol (ICP) platform presented unique challenges that significantly tested our adaptability and ability to learn quickly. We eventually were able to figure it out through a lot of trial and error.

## Accomplishments that we're proud of
We are incredibly proud of creating a tool that not only achieves our goal of unbiased grading but also significantly reduces the time teachers spend grading. The system allows teachers to efficiently grade and return tests to students. Our system's ability to handle a diverse array of subjects and question types with the same level of precision is an accomplishment that speaks to the versatility and robustness of our solution.

What we learned
This project was a deep dive into the capabilities of AI in education. We learned about the intricacies of natural language processing, image recognition, and the importance of user experience design. It was enlightening to explore the ethical considerations of AI in grading and the impact of technology on educational equity. We also gained valuable experience in teamwork and project management, navigating challenges and celebrating milestones together.

What's next for CrewAI
Looking ahead, we are excited to expand our application's capabilities. We plan to introduce more personalized feedback options, adapt our system to support additional test formats, and enhance our AI to handle even more complex grading scenarios. Our vision is to make unbiased, AI-powered grading accessible to educators worldwide, transforming the educational landscape by enabling more focused, effective teaching and learning experiences.
