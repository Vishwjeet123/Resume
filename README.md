# Resume
#my resume
%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
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

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
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

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Vishwjeet Singh} \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +91-8083560308 ~ \href{mailto:ayushraichand1@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{svishwjeet737@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/ayush-kumar-1011/}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/vishwjeet-singh/}}  ~
    \href{https://github.com/ayush1011}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/Vishwjeet123}}
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {IES college of Technology, Bhopal}{Aug 2019 -- May 2023}
      {Bachelor of Technology in Electronics and Communication Engineering}{Bhopal, M.P}
  \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{Relevant Coursework}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Data Structures
                \item Operating Systems
                \item Algorithms Analysis
                \item Database Management
                \item Computer Networks
                \item Computer Architecture
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd


%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, C,C++, HTML/CSS, JavaScript} \\
     \textbf{Developer Tools}{: VS Code, Code Block, AWS} \\
     \textbf{Databases}{: MongoDB, Oracle} \\
     \textbf{Mobile and Web Application}{React}
    }}
 \end{itemize}
 \vspace{-16pt}


%-----------EXPERIENCE-----------
\section{Professional Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Oasis Infobyte}{Mar 2023 -- Mar 2023}
      {Java Development Intern $|$ Full Stack}{South West, New Delhi}
      \resumeItemListEnd

    \resumeSubheading
      {Kodacy}{Dec 2022 -- Dec 2020}
      {Robotics Intern}{Virtual}
      \resumeItemListStart
        
    \resumeItemListEnd
    
%     \resumeSubheading
%       {FollowClass} {Dec 2017 -- Jan 2018}
%       {Software Development Intern}{Bangalore, Karnataka}
%       \resumeItemListStart
%         \resumeItem{Developed a Plagiarism checker to identify copied reports submission, answer
% sheets etc.}
% \resumeItem{Integrated Cron jobs using RabbitMQ for improving efficiency of portal.}
% \resumeItem{Tech stack - MongoDB, Node JS, Angular JS , RabbitMQ, Redis etc using
% express Framework.}
       
%     \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-14pt}

%-----------PROJECTS-----------
\section{Academic Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Google-clone} $|$ \emph{HTML, CSS, JavaScript, React,API}}{May 2023}
          \resumeItemListStart
            \resumeItem{Built an Search Engine using React with the express structure to render Assignment of various APIs while providing
Google, programmable Search Engine.}
          \resumeItemListEnd
          
    \resumeProjectHeading
          {\textbf{Remote Monitoring System For Cold Storage Warehouse } $|$ \emph{IoT, Arduino, Think Speak}}{May 2023}
          \resumeItemListStart
            \resumeItem{Developed an Warehouse to analyse temperature, humidity,Air Quality of this Warehouse.}
            \resumeItem{Used technical stacks are Arduino, Iot, Think Speak Software, Sensors.}
            \resumeItem{Team Size - 4}
            \resumeItem{Role - Team Member}
          \resumeItemListEnd
    \resumeProjectHeading
          {\textbf{Smart Car Parking System} $|$ \emph{Arduino, Sensor}}{May 2022}
          \resumeItemListStart
            \resumeItem{Built-up Smart Parking System For Smart Cities.}
            \resumeItem{Used technical stacks are Arduino, LCD, Sensors}
            \resumeItem{Team Size - 4}
            \resumeItem{Role - Team leader}
          \resumeItemListEnd
       
    \resumeSubHeadingListEnd
\vspace{-13pt}


%-----------CERTIFICATION---------------
\section{Certifications and Awards}
    % \resumeSubHeadingListStart
    %     \resumeSubheading{Fraternity}{Spring 2020 -- Present}{President}{University Name}
            \resumeItemListStart
                \resumeItem{2nd winner of Codactive 1.o state level Hacathon -BSIT Bhopal}
                \resumeItem{Problem Solving of Leetcode  https://leetcode.com/Vishwjeet123/}
                
            \resumeItemListEnd
        
    % \resumeSubHeadingListEnd
\vspace{-10pt}


%-----------INVOLVEMENT---------------
\section{Position of Responsibilities / Extracurricular}
    % \resumeSubHeadingListStart
    %     \resumeSubheading{Fraternity}{Spring 2020 -- Present}{President}{University Name}
            \resumeItemListStart
                \resumeItem{\textbf{INFORIA 2k21} - Participant As a Project Exhibition,Bhopal M.P}
                \resumeItem{\textbf{INFORIA 2k22} - Coordinator As a Project Exhibition,Bhopal M.P}
            \resumeItemListEnd
        
    % \resumeSubHeadingListEnd


\end{document}
