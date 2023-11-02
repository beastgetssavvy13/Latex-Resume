# Latex-Resume
%-------------------------
% Resume in Latex
% Author: Kavish Pandit
% Based off of: https://github.com/sb2nov/resume
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}
\usepackage{tikz}
\usepackage{atbegshi}
\usepackage{etoolbox}




%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}
\usepackage{xcolor}
\urlstyle{same}
\definecolor{mydarkblue}{HTML}{00009B}  % This is a hex code for a dark blue.
\definecolor{myblue}{HTML}{0000FF}      % This is a hex code for standard blue.


\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=mydarkblue,   % color of internal links
    citecolor=mydarkblue,   % color of links to bibliography
    filecolor=magenta,    % color of file links
    urlcolor=mydarkblue,    % color of external links
}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generated pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

% Custom command to add watermark with a hyperlink at the end of the document
% \newcommand\AddWatermarkAtEnd{%
%   \AtEndDocument{%
%     \AtBeginShipoutNext{%
%       \AtBeginShipoutUpperLeftForeground{%
%         \begin{tikzpicture}[remember picture,overlay]
%           \node [anchor=south, yshift=10mm, font=\fontsize{7pt}{7pt}\selectfont\itshape] at (current page.south) {
%             \href{http://www.example.com}{Resume Coded By Kavish Pandit}
%           };
%         \end{tikzpicture}%
%       }%
%     }%
%   }%
% }
% \AddWatermarkAtEnd

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Kavish Pandit} \\ \vspace{1pt}
    \vspace{2pt}
    \small \raisebox{-0.1\height}\faPhone\ +91-7011241957 ~ \href{mailto:x@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{kavish.pandit178@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/kavishpandit-b9915b1b1/}{\raisebox{-0.2\height}\faLinkedin\ \underline{LinkedIn}}  ~
    \href{https://github.com/beastgetssavvy13}{\raisebox{-0.2\height}\faGithub\ \underline{Github}}
       \vspace{-4pt}
\end{center}
\begin{center}
{A reliable and highly-rated team player, recognized as an award-winning Toastmaster with a passion for volunteering and a proven track record in building features and problem-solving. Eagerly looking to leverage the in-depth MEM program curriculum, with an ambition to harness technology and management expertise to deliver efficient solutions.}
\end{center}
    


   \vspace{-20pt}
%-----------EDUCATION-----------

\section{Education}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Vellore Institute of Technology}{July 2017 -- March 2021}
      {Information Technology }{Vellore, Tamil Nadu}
      \resumeItemListStart
        \resumeItem{CGPA: 9.13/10, as per Indian grading scale; 3.925/4, as per official WES Evaluation}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
\vspace{-16pt}


%-----------EXPERIENCE-----------
\section{Professional Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {OfBusiness}{August 2021 -- Present}
      {Software Engineer Level II}{Gurugram, Harayana}
      \resumeItemListStart
        \resumeItem{Single-handedly engineered \textbf{Oxyzo's MIS dashboard} in a record timeframe, setting a new benchmark for rapid development and accelerating quarterly \textbf{RBI audit processes by 50\%} compared to standard practices.}
        \resumeItem{Engineered and overhauled a \textbf{consolidated dashboard} for credit ratings, achieving a \textbf{40\%} more efficient \textbf{data coupling} over conventional systems.}
        \resumeItem{Co-engineered the front-end creation of \textbf{Oxyzo's Supply Chain Financing platform}, delivering critical onboarding modules and user interfaces with enhanced functionality, significantly accelerating product time-to-market.}
      \resumeItemListEnd
      
    \resumeSubheading
      {Tata Health, Tata Group}{May 2021 -- August 2021}
      {Associate Product Manager}{Remote}
      \resumeItemListStart
        \resumeItem{\textbf{Orchestrated sachet tablet labeling} and prescription mapping, markedly enhancing medication management.}
        \resumeItem{Identifying the existing disparities between the current state of \textbf{medical space} and an optimally functioning system.}
    \resumeItemListEnd
     \resumeSubheading
      {EPAM Systems, Inc.}{March 2021 -- May 2021}
      {Associate Software Engineer}{Hyderabad, Telangana}
      \resumeItemListStart
        \resumeItem{Adhering to company design patterns, a Java Spring Boot automated service and \textbf{CRM framework} were developed, streamlining \textbf{HR LMS processes} and improving responsiveness.}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-10pt}

%-----------LEADERSHIP EXPERIENCE---------------
\section{Leadership Experience}
    \resumeSubHeadingListStart
        \resumeSubheading{Toastmasters International}{April 2023 -- Present}{General Secretary and Associate Vice President, Education}{Gurugram Toastmasters Club}
            \resumeItemListStart
                \resumeItem{\textbf{Secretary Chair}, led a team, enhanced meeting, and elections procedures, boosting club performance metrics by \textbf{25\%}.}
                \resumeItem{\textbf{Chaired Associate Vice President}, revamped agendas and nominations, realizing advancements in club operations.}
            \resumeItemListEnd
  \resumeSubheading
  {\href{https://www.thebasicsproject.com/}{The Basics Project Foundation}}{July 2023 -- Present}{Volunteering Head}{Delhi, India}
  \resumeItemListStart
      \resumeItem{\textbf{Streamlined procedures} for team and pioneered recurring contribution, \textbf{20\% improvement} in process tracking.}
      \resumeItem{Spearheaded \textbf{team}, formulated and brainstormed strategies, optimizing \textbf{donor engagement} and contribution efficiency.}
        \vspace{-9pt}
  \resumeItemListEnd
    \resumeSubheading{Global Governance Initiative}{March 2021 -- December 2021}{Global Impact MBA Scholar}{Remote, India}
            \resumeItemListStart
                \resumeItem{Leveraged \textbf{Schrodinger tool} for complex cases, outpacing traditional methods; \textbf{collaborated with co-founders}.}
                \resumeItem{Collaborated with cohort members to enhance case study solutions, achieving a \textbf{40\% increase} in efficiency.}
            \resumeItemListEnd   
    \resumeSubheading{eVidyaloka Trust}{August 2020 -- Feb 2021}{Lead Content Developer}{Remote, India}
            \resumeItemListStart
                \resumeItem{Played \textbf{an imperative role} in a team that achieved a quality enhancement in \textbf{NGO's grade 6-10} math curricula.}
                \resumeItem{Assisted with \textbf{40+ assignments} and quizzes, upgrading the grade \textbf{6-10 educational toolkit}.}
            \resumeItemListEnd   
        
    \resumeSubHeadingListEnd
   \vspace{-15pt}
%-----------PUBLICATIONS-----------
\section{Publications}
\vspace{-5pt}
\resumeSubHeadingListStart
 \resumeProjectHeading
    {\textbf{\href{https://drive.google.com/file/d/168whyUBm9_N5lXw0gwGr-yDcYA2sMvys/view}{Classification of E-commerce online auctions and prediction of seller reputation}}}{June 2019}
      \resumeItemListStart
        \resumeItem{Conducted research on online auctions and developed techniques to predict seller reputation.}
        \resumeItem{Utilized advanced algorithms, specifically \textbf{Multinomial Naive Bayes and SVD}, to enhance the data mining process.}
      \resumeItemListEnd
      \vspace{-2pt}
\vspace{-10pt}
\resumeSubHeadingListEnd


%-----------PROJECTS-----------

\section{Projects}

\resumeSubHeadingListStart
\vspace{-5pt}
    \resumeProjectHeading
        {\textbf{Post-Covid Refinement of Dynamic Agile Methodologies for Hybrid-First Work Culture}}{November 2023}
    \resumeItemListStart
        \resumeItem{Demonstrated Scrumban's efficacy, boosting productivity by \textbf{35\%}, merging \textbf{Scrum and Kanban advantages}.}
        
        \resumeItem{ \textbf{Conducted 4 surveys and 12 interviews} and recognized critical gaps with the current agile methodologies.} 
        
         \resumeItem{Addressed \textbf{project management challenges} in hybrid work \textbf{post-COVID} through surveys and interviews and research paper currently undergoing review, to be published in January 2024.}
    
    \resumeItemListEnd
    \vspace{-15pt}
    \resumeProjectHeading
        {\href{https://github.com/beastgetssavvy13/pixelated-contact-keeper}{\textbf{Contact Keeper MERN App} $|$ \emph{ReactJs, NodeJs}}}{January 2021}
    \resumeItemListStart
        \resumeItem{Amplified API  \textbf{response by 65\%} using Mongoose, integrated with \textbf{MongoDB Atlas} for database management.}
        \resumeItem{Improved traditional contact management \textbf{productivity by 70\% } with a \textbf{JWT-authenticated MERN app.}}
    \resumeItemListEnd
\vspace{-15pt}
    \resumeProjectHeading
        {\href{https://github.com/beastgetssavvy13/task-manager-api-prod}{\textbf{Task Manager CRUD Web App} $|$ \emph{NodeJs, MongoDb, ReactJs}}}{January 2021}
    \resumeItemListStart
        \resumeItem{Outperformed traditional task management \textbf{by 80\%} with a \textbf{Node.js/MongoDB} API for task logging, and  profiles.}
        \resumeItem{Transformed traditional task operations, reaching a 
        \textbf{75\% boost} in process efficiency, verified using Postman.}
    \resumeItemListEnd
\vspace{-15pt}
    \resumeProjectHeading
        {\href{https://github.com/beastgetssavvy13/chennai-water-level-machine-learning}{\textbf{Chennai Water Level prediction using ML Algorithms} $|$ \emph{Time Series Analysis, Linear Regression}}}{October 2020}
    \resumeItemListStart
       \resumeItem{Achieved over \textbf{80\% accuracy} in neural network prediction using sentiment data integration.}
        \resumeItem{Used \textbf{Kaggle data} to analyze rainfall and storage; \textbf{applied regression and time series} for accurate water level predictions.}
    \resumeItemListEnd
\vspace{2pt}
\resumeSubHeadingListEnd



%-----------PROFESSIONAL CERTIFICATIONS-----------
\section{Professional Certifications}
\resumeSubHeadingListStart
\vspace{-15pt}  
    \resumeProjectHeading
        {\textbf{}}{}
        \vspace{-15pt}
   \resumeItemListStart
    \resumeItem{\href{https://www.linkedin.com/learning/certificates/75c3888e68d89683a8dcb48f68867e1491cd4a3f8fb420a74f29d34493b00919}{{Becoming a Product Manager: A Complete Guide} $|$ \emph{LinkedIn Learning, Cole Mercer and Evan Kimbrell}}}
    \resumeItem{\href{https://www.coursera.org/account/accomplishments/certificate/H6JNY3AXCZ3F}{{Machine Learning with Big Data} $|$ \emph{Coursera}}}
    \resumeItem{\href{https://ninjasfiles.s3.amazonaws.com/certificate610561b012efde379407bbb99a3509a8cbe47b.pdf}{{Data Structures \& Algo with Java} $|$ \emph{Coding Ninjas}}}

    \resumeItem{\href{https://drive.google.com/file/d/1yi4WTO5F-VUxX9AKJisYFzAKeRj_Z83-/view}{{National Workshop on Google cloud platform} $|$ \emph{Google Cloud Platform}}}
    \resumeItem{\href{https://www.coursera.org/account/accomplishments/certificate/2VC5XAJ3BCJ7}{{Database Management Essentials} $|$ \emph{Coursera}}}
\resumeItemListEnd


\vspace{2pt}
\resumeSubHeadingListEnd




%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
    \small\item \textbf{Languages}{: Java, JavaScript, ReactJs, HTML/CSS, SQL, MongoDB, Python, Shell, NodeJs, TypeScipt, Latex} 
    \vspace{-6pt}
    \small\item \textbf{Developer Tools}{: VS Code, PostMan, IntelliJ, Figma, Robo3T, Eclipse, Google Cloud Platform, Android Studio}
    \vspace{-6pt}
    \small\item \textbf{Other Skills}{: Cross-Functional Leadership, Agile Methodology, Product Management, Project Management}
\end{itemize}
\vspace{-12pt}


%-----------PROGRAMMING SKILLS-----------
\section{Achievements}
\resumeSubHeadingListStart
\vspace{-5pt}
    \resumeProjectHeading
        {\textbf{Distinguished Recognition and Accolades Secured at Toastmasters International Club}}{August 2023}
    \resumeItemListStart
          \resumeItem{Received the \textbf{Best Speaker Award} for showcasing outstanding communication skills.}
        \resumeItem{Honored with the \textbf{Best Evaluator Award} for consistent constructive feedback.}
        \resumeItem{Achieved the \textbf{Best Auxiliary Role Award} for significant contributions at both club and area levels.}

    \resumeItemListEnd
    \vspace{-15pt}
    \resumeProjectHeading
       {\textbf{University-Level Academic Achievement} }{June 2021}
    \resumeItemListStart
        \resumeItem{Secured \textbf{23rd rank} within the Information Technology branch at VIT University.}
    \resumeItemListEnd
\vspace{-15pt}
    \resumeProjectHeading
     {\textbf{Distinguished Pan-India Cohort Selection for Global Governance Initiative}}{March 2021}
    \resumeItemListStart
      \resumeItem{Admitted to the elite \textbf{Global Governance Impact MBA } Scholars program with less than \textbf{10\% acceptance rate}.}
     
    \resumeItemListEnd
\vspace{-15pt}    
    \resumeProjectHeading
        {\textbf{International Symposium Publication Achievement}}{January 2019}
    \resumeItemListStart
        \resumeItem{Publication got selected for \textbf{RDAIS Symposium}, \textbf{Botswana}.}
    \resumeItemListEnd
\vspace{-15pt}
\resumeProjectHeading
        {\textbf{Lead Director at VIT Film Society}}{August 2018}
    \resumeItemListStart
        \resumeItem{Directed pivotal films highlighting \textbf{girls' safety and sanitation}, in partnership with a team.}
    \resumeItemListEnd
\vspace{-15pt}
\resumeProjectHeading
        {\textbf{Academic Excellence Award by Kashmiri Welfare Society}}{January 2014}
    \resumeItemListStart
        \resumeItem{Awarded and commended for achieving a perfect \textbf{CGPA of 10 in Grade 10} studies.}
    \resumeItemListEnd
\vspace{-15pt}

\resumeProjectHeading
        {\textbf{Digital Education Through YouTube Content Production}}{May 2012}
    \resumeItemListStart
        \resumeItem{Accumulated over \textbf{90k+ views} producing original educational videos in collaboration with peers.}
        \resumeItem{Initiated this content-driven endeavor during school years, targeting diverse educational fields.}
    \resumeItemListEnd
\vspace{-15pt}
\resumeSubHeadingListEnd
\vspace{-12pt}
\end{document}


Handcrafted and coded Professional Resume on Latex
