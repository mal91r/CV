# %-------------------------
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
    {\Huge \scshape Artem Malanin} \\ \vspace{1pt}
    Moscow, Russia \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +79161727616 ~ \href{admalanin@edu.hse.ru}{\raisebox{-0.2\height}\faEnvelope\  \underline{admalanin@edu.hse.ru}} ~ 
    \href{https://github.com/mal91r}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/mal91r}} ~
    \href{https://gitlab.com/mal91r}{\raisebox{-0.2\height}\faGithub\ \underline{gitlab.com/mal91r}}
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
        {National Research University "Higher School of Economics"} % Organization
        {09/2021 - present} % Date
        {BSc in Computer Science, Software Engineering department, 7.17 GPA} % Job title
        {Moscow, Russia} % Location
    \resumeSubheading
        {Bauman Engineering School 1580} % Organization
        {09/2019 - 08/2021} % Date
        {IT-class, 5.0 GPA} % Job title
        {Moscow, Russia} % Location
    \resumeSubheading
        {Secondary School 1205} % Organization
        {09/2010 - 08/2019} % Date
        {With advanced learning of foreign languages, 5.0 GPA} % Job title
        {Moscow, Russia} % Location
    
  \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{Relevant Courses}
    %\resumeSubHeadingListStart
        \begin{multicols}{2}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small C\# Programming
                \item Algebra
                \item Discrete Mathematics
                \item Calculus 
                \item Economics
                \item C++ Programming Basics
                \item Computer Practicum on Calculus in Python
                \item Computer Practicum on Algebra in Python
                \item Introduction into Software Engineering
                \item Introduction to Microsoft Cloud Technologies
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
        \resumeProjectHeading
            {\href{https://github.com/mal91r/Challengify}
            {\textbf{Challengify}} $|$ \emph{C\#}}{March 2022}
            \resumeItemListStart
            \resumeItem{Developed MVC system on C\# using .Net Core 5.0 and Entity Framework}
            \resumeItem{Worked with database and basic authentication using LINQ.}
            \resumeItemListEnd
            \vspace{-13pt}
              
        \resumeProjectHeading
            {\href{https://github.com/mal91r/messenger_WebApi}
            {\textbf{Messenger}} $|$ \emph{C\#}}{March 2022}
            \resumeItemListStart
            \resumeItem{Created simple messenger on Asp.net core Web Api using Swagger.}
            \resumeItemListEnd 
            \vspace{-13pt}
            
        \resumeProjectHeading
            {\href{https://github.com/mal91r/TransportSimulator}
            {\textbf{Transport}} $|$ \emph{C\#}}{February 2022}
            \resumeItemListStart
            \resumeItem{OOP and SOLID final task in University.}
            \resumeItemListEnd 
            \vspace{-13pt}
        
        \resumeProjectHeading
            {\href{https://github.com/mal91r/FractalBuilder}
            {\textbf{Fractal Paint}} $|$ \emph{C\#}}{January 2022}
            \resumeItemListStart
            \resumeItem{Created app that draw the selected fractal using WPF.}
            \resumeItemListEnd 
            \vspace{-13pt}
              
        \resumeProjectHeading
            {\href{https://github.com/mal91r/TextEditor}
            {\textbf{Text Editor}} $|$ \emph{C\#}}{December 2021}
            \resumeItemListStart
            \resumeItem{Created text editor on C\# using WinForms.}
            \resumeItemListEnd 
            \vspace{-13pt}
            
        \resumeProjectHeading
            {\href{https://github.com/mal91r/FileManager}
            {\textbf{File Manager}} $|$ \emph{C\#}}{November 2021}
            \resumeItemListStart
            \resumeItem{Created console app to work with directories on C\#.}
            \resumeItemListEnd 
            \vspace{-13pt}
            
        \resumeProjectHeading
            {\href{https://github.com/mal91r/PhotoBot_TG}
            {\textbf{Photo Bot}} $|$ \emph{Python}}{August 2021}
            \resumeItemListStart
            \resumeItem{Created bot to work with photos in Telegram on Python using telebot api.}
            \resumeItemListEnd 
            \vspace{-13pt}
            
        \resumeProjectHeading
            {\href{https://github.com/mal91r/Balaboba_YandexPracticum}
            {\textbf{Balaboba Bot}} $|$ \emph{Python}}{July 2021}
            \resumeItemListStart
            \resumeItem{Created bot to work with Yandex.Balaboba on Python using url requests. YandexPracticum course.}
            \resumeItemListEnd 
            
    \resumeSubHeadingListEnd
\vspace{-15pt}


%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: C\#, C++, Python, SQL} \\
     \textbf{Developer Tools}{: Visual Studio, Rider, CLion} \\
     \textbf{Technologies/Frameworks}{: .Net.Core, GitHub, Docker} \\
     \textbf{Operational System}{: Windows}
    }}
 \end{itemize}
 \vspace{-16pt}


%-----------Soft SKILLS-----------
\section{Soft Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Russian - native speaker, English - advanced} \\
    }}
 \end{itemize}
 \vspace{-16pt}
 
 
\section{Achievements}
    \resumeSubHeadingListStart
        \resumeProjectHeading
            {\textbf{Olympiad "Fiztech" in physics} $|$ \emph{Winner - TOP 0.5\%}}{2021}
        \resumeProjectHeading
            {\textbf{"Rosatom" Olympiad in Mathematics} $|$ \emph{Winner - TOP 1\%}}{2021}
        \resumeProjectHeading
            {\textbf{University Olympiad "Belchonok" in IT} $|$ \emph{Winner - TOP 2.5\%}}{2021}
    \resumeSubHeadingListEnd
 
\end{document}
