# COMP664: Deep Learning

Instructor: [Colin Raffel](http://colinraffel.com)

TA: [Zhen Wei](https://www.cs.unc.edu/~zhenni/)

Term: Spring 2023

Meeting time: Mondays and Wednesdays, 12:30-1:45pm

Classroom: FB 009 or on Zoom (see Sakai for the link)

Office hours: By appointment

Deep learning is the branch of machine learning focused on training neural networks.
Neural networks have proven to be powerful across a wide range of domains and tasks, including computer vision, natural language processing, speech recognition, and beyond.
The success of these models is partially thanks to the fact that their performance tends to improve as more and more data is used to train them.
Further, there have been many advances over the past few decades that have made it easier to attain good performance when using neural networks.
In this course, we will provide a thorough introduction to the field of deep learning.
We will cover the basics of building and optimizing neural networks in addition to specifics of different model architectures and training schemes.
We will use portions of the "[Dive into Deep Learning](https://d2l.ai/)" textbook and will have a standard lecture/homework/exam format.

## Prerequisites

Students need to have taken the following courses:
  - Machine learning (one of COMP562, COMP755, STOR565, or equivalent)
  - Linear algebra (one of MATH210, MATH347, MATH577, or equivalent)
  - Multivariate calculus (one of MATH233, MATH522, or equivalent)
  
Further, it is recommended that students have some basic familiarity with statistical concepts.
Finally, students must be proficient in reading and writing Python code.

## Schedule

The following schedule is a guess; we may deviate from this schedule somewhat if things take significantly longer or shorter to get through.
Students should read the associated textbook section/chapters before class.
All readings refer to corresponding sections in [Dive into Deep Learning](http://d2l.ai).

| Date            | Subject                                                        | Reading            | Homework              |
| --------------- | -------------------------------------------------------------- | ------------------ | --------------------- |
| Mon, 1/9        | Class introduction, background, logistics                      | 2.1-2.7 (optional) |                       |
| Wed, 1/11       | Linear regression                                              | 3.1-3.5            | H1 assigned           |
| Mon, 1/16       | No class                                                       | —                  |                       |
| Wed, 1/18       | Logistic regression                                            | 4.1-4.5            | H1 due, H2 assigned   |
| Mon, 1/23       | Gradient descent & adaptive gradient methods                   | 12.1-12.6, 12.10   |                       |
| Wed, 1/25       | Under/overfitting, regularization                              | 3.6-3.7, 5.6       | H2 due, H3 assigned   |
| Mon, 1/30       | Multilayer perceptrons                                         | 5.1-5.2            |                       |
| Wed, 2/1        | Backpropagation, numerical stability                           | 5.3-5.4            | H3 due, H4 assigned   |
| Mon, 2/6        | Automatic differentiation                                      |                    |                       |
| Wed, 2/8        | Convolutional neural networks                                  | 7.1-7.5            | H4 due, H5 assigned   |
| Mon, 2/13       | No class                                                       | —                  |                       |
| Wed, 2/15       | Batch/layer normalization & residual connections               | 8.5-8.6            | H5 due, H6 assigned   |
| Mon, 2/20       | Midterm Review                                                 | —                  |                       |
| Wed, 2/22       | Midterm                                                        | —                  |                       |
| Mon, 2/27       | Sequences and recurrent neural networks                        | 9.1-9.7            |                       |
| Wed, 3/1        | Recurrent neural networks 2                                    | 10.1-10.4          | H6 due, H7 assigned   |
| Mon, 3/6        | Sequence-to-sequence learning                                  | 10.5-10.8          |                       |
| Wed, 3/8        | Attention 1                                                    | 11.1-11.4          | H7 due, H8 assigned   |
| Mon, 3/13       | No class                                                       | —                  |                       |
| Wed, 3/15       | No class                                                       | —                  |                       |
| Mon, 3/20       | Attention 2                                                    | 11.5-11.6          |                       |
| Wed, 3/22       | The Transformer                                                | 11.7               | H8 due, H9 assigned   |
| Mon, 3/27       | Encoder-only Transformers                                      | 15.8-15.10         |                       |
| Wed, 3/29       | Decoder-only Transformers                                      | 11.9               | H9 due, H10 assigned  |
| Mon, 4/3        | Transformers for Vision                                        | 11.8               |                       |
| Wed, 4/5        | Semi-supervised and self-supervised learning                   | —                  | H10 due, H11 assigned |
| Mon, 4/10       | Flow- and diffusion-based models                               | —                  |                       |
| Wed, 4/12       | Generative Adversarial Nets and Variational Autoencoders       | 20.1-20.2          | H11 due, H12 assigned |
| Mon, 4/17       | Deep learning engineering                                      | 13.5-13.6          |                       |
| Wed, 4/19       | Distribution shift; fairness, accountability, and transparency | 4.7                | H12 due               |
| Mon, 4/24       | (extra lecture session for make-up)                            | —                  |                       |
| Wed, 4/26       | Final exam review                                              | —                  |                       |
| Final exam slot | Final exam                                                     | —                  |                       |

## Grading

  1. **Homework**, 48 points: There will be 12 homework assignments. Each homework assignment will be assigned on Wednesday and due the following Wednesday. Homework will consist of some combination of math and coding. Each homework is worth 4 points.
  1. **Midterm**, 22 points: The midterm will take place on 2/27 and will cover all topics discussed before the midterm.
  1. **Final Exam**, 30 points: The final exam will take place during our scheduled final exam slot and will cover all topics discussed in the class.

## Late work, collaboration rules, and the honor code

You can replace your worst homework grade with a perfect grade (4/4), which effectively excuses you from a single homework.
I can grant you an extension on a homework due to a life emergency, but you must request an extension at least 24 hours before the homework is due.

You are welcome to work together with other students on the homework.
You are also welcome to use any resources you find (online tutorials, textbooks, papers, etc.) to help you complete the homework.
However, **you must list any collaboration or resources you used to complete each homework on each assignment**.
If you hand in homework that involved collaboration and/or makes use of content that you did not create and you do not disclose this, you will get a 0 for that homework.

All students are expected to follow the guidelines of the [UNC honor code](http://honor.unc.edu).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honor code, feel free to ask me.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited at UNC-Chapel Hill.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Director of Title IX Compliance/Title IX Coordinator (Adrienne Allison, adrienne.allison@unc.edu), Report and Response Coordinators (Ew Quimbaya-Winship, eqw@unc.edu; Rebecca Gibson, rmgibson@unc.edu; Kathryn Winn kmwinn@unc.edu), Counseling and Psychological Services (CAPs) (confidential) in Campus Health Services at (919) 966-3658, or the Gender Violence Services Coordinators (confidential) (Cassidy Johnson, cassidyjohnson@unc.edu; Holly Lovern, holly.lovern@unc.edu) to discuss your specific needs.
Additional resources are available at http://safe.unc.edu.

## Resources

The University of North Carolina at Chapel Hill facilitates the implementation of reasonable accommodations, including resources and services, for students with disabilities, chronic medical conditions, a temporary disability or pregnancy complications resulting in difficulties with accessing learning opportunities.
All accommodations are coordinated through the Accessibility Resources and Service Office. See the ARS Website for contact information: https://ars.unc.edu or email ars@unc.edu.
Relevant policy documents as they relate to registration and accommodations determinations and the student registration form are available on the ARS website under the About ARS tab.

CAPS is strongly committed to addressing the mental health needs of a diverse student body through timely access to consultation and connection to clinically appropriate services, whether for short or long-term needs. Go to their [website](https://caps.unc.edu/) or visit their facilities on the third floor of the Campus Health Services building for a walk-in evaluation to learn more.


## Spring 2023 Course Delivery

Whenever possible, I will give lectures live in FB009.
All lectures will be simultaneously livestreamed over Zoom, and recordings of each lecture will be made available after each class session.
In the event of illness or travel, I will give lectures over Zoom and not in-person at FB009.

## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.
