---
layout: page
title: About me
---

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
\usepackage[T1]{fontenc}
\usepackage{xcolor}
\usepackage{sectsty}


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
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.0in}
\addtolength{\topmargin}{0in}
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
% Custom commands\
\newcommand{\quotationmark}[1]{“#1”}

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

\newcommand{\resumeSubheadingss}[8]{
   \vspace{-2pt}\item
   \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      #3 & \textit{\small #4} \\
      #5 & #6 \\
      #7 & #8 \\
   \end{tabular*}\vspace{-6pt}
}

\newcommand{\resumeSubheadings}[6]{
   \vspace{-2pt}\item
   \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      #3 & \textit{\small #4} \\
      #5 & #6 \\
   \end{tabular*}\vspace{-6pt}
}

\newcommand{\resumeSubheading}[4]{
   \vspace{-2pt}\item
   \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      {\small#3} & {\small #4} \\
   \end{tabular*}\vspace{-3pt}
}




\newcommand{\resumeSubSubheading}[2]{
   \item
   \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
   \end{tabular*}\vspace{-3pt}
}


\newcommand{\resumePaperSubheading}[2]{
   \item
   \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textit{\small #2} \\
   \end{tabular*}\vspace{-3pt}
}

\newcommand{\resumePapersSubheading}[2]{
   \item
   \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      {#1} \\
   \end{tabular*}\vspace{-3pt}
}

\newcommand{\resumeProjectHeading}[2]{
   \item
   \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
   \end{tabular*}\vspace{-3pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
   \newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\newcommand{\resumeSubHeadingsListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
   \newcommand{\resumeSubHeadingsListEnd}{\end{itemize}}

\newcommand{\resumeItemListStart}{\begin{itemize}}
   \newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-3pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}
   
   \begin{center}
      {\Large \bfseries\textsc{Curriculum Vitae}} \\ \vspace{10pt}
      \small \raisebox{-0.1\height } Jung Hun Phee $\mid$ pheeeeee@yonsei.ac.kr $\mid$ \href{https://github.com/}{\raisebox{-0.2\height}\faGithub\ \underline{pheeeeee.github.io}}
      %\small \raisebox{-0.1\height } Yeo Jin Jung / jjung1089@gmail.com / Statistics Ph.D. 
      % \href{https://github.com/}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/kelseyj3411}}
      \vspace{-10pt}
   \end{center}
   
   %-----------EDUCATION-----------
   \sectionfont{\color{blue}}
   \section{Education}
   \resumeSubHeadingsListStart
   \resumeSubheadings
   {Yonsei University}{Sep. 2022 -- Present}
   {Master of Arts in Statistics and Data Science in progress}{\textnormal{Seoul, South Korea}}
   {\small\textnormal{Total GPA of %4.30/4.30}}{}
   }}{}
   %{\small Thesis: \quotationmark{Generalized additive models using Bayesian model selection with mixtures of g-priors}}{}
   %{Total GPA of 4.30/4.30 (\textbf{4.00}/4.00)}{}
   
   \resumeSubheadings
   {Yonsei University}{Feb. 2021 -- Aug. 2022}
   {Bachelor of Arts in Mathematics(Minor in Statistics)}{\textnormal{Seoul, South Korea}}
   {\small Thesis: \quotationmark{Quantum Algorithms for the Hidden Shift Problem}}{}
   %{Total GPA of 4.02/4.30 \textbf{(98.2/100)}{}
   
   {\small \small Math and Stat GPA of 4.03/4.30 }{}
   
    \resumeSubheadings
   {Yonsei University}{Feb. 2016 -- Aug. 2022}
   {Bachelor of Arts in Economics}{\textnormal{Seoul, South Korea}}
   {\small Thesis: \quotationmark{Heterogeneous Responses to Monetary Policy Shock in Industry Levels \\and Responses of Equity Market : Case of Korea}}{}
   %{Total GPA of 4.02/4.30 \textbf{(98.2/100)}{}
   
   {\small \small \textnormal{Econ GPA of 4.03/4.30, Total GPA of 3.97/4.30 }}{}
   
   \resumeSubheadings
   {University of California, Berkeley}{Jan. 2019 -- Dec. 2019}
   {Undergraduate Exchange Program}{\textnormal{Berkeley, California, USA}}
   {\small (*Grades are not included in the Undergraduate GPA in the transcript.)}{}
   
   \resumeSubheadings
   {Leave of Absence}{2017}
   {}{}
   {}{}
   
   \resumeSubHeadingsListEnd
   \vspace{-6pt}

     %-----------INTERESTS-----------
   \section{Fields of Interests}
   Robustness of Machine Learning, Theoretical Computer Science, Spline Theory, Functional Analysis, Harmonic Analysis, Microeconomics, Applications to machine learning, inverse problem in medical imaging, and finance.


  %-----------AWARDS / HONORS-----------
   \section{HONORS / AWARDS}
   \resumeSubHeadingsListStart
   \resumeSubheadings
   {Honorable Mention, Qiskit Hackerton Korea 2022}{2022}
   {- Proved the Quantum Algorithm for the Hidden Shift Problem of bent functions works \\with significant time speed up.}{}
   {}{}

    \resumeSubheadings
   {Honors, Yonsei University}{2016}
   {}{}
   {}{}


    \resumeSubheadings
   {The Minister of Economy and Finance Award }{2014}
   {- Conducted the Korean ODA policy, which was selected as the best proposal \\in the Economic Policy Proposal Contest held by the Korean Ministry of Economy and Finance}{}
   {}{}

    \resumeSubheadings
   {Math Award, Waterloo University }{2010}
   {Best Grade(1st Place) in Canada}{}
   {}{}

   \resumeSubHeadingsListEnd

    \newpage

     %-----------Scholarships-----------
   \section{Scholarships}
   \resumeSubHeadingsListStart
   \resumeSubheadings
   {Brain Korea 21 Scholarships, National Research Foundation of Korea}{2022 -- present}
   {(Merit-based)}{}
   {}{}



    \resumeSubheadings
   {National Merit Scholarship, Republic of Korea }{2016 -- 2020}
   {(Merit-based) Full Tuition Scholarship for four years of University %(29,681,000 KRW)
   }{}
   {}{}

   \resumeSubHeadingsListEnd

      
   %-----------EXPERIENCE-----------
   %-----------research-----------
   \section{Research Experience}
   \resumeSubHeadingListStart
   \resumeSubheadings
   {[1] Quantum Algorithms for the Hidden Shift Problem}{2022}
   {\small\textnormal{(Co-authored with Boseong Kim, Sekang Kwon, Sehoon Bahng, Inhyuk Oh, Adel Sohbi, Hyukjoon Kwon)}}{}
   {}{}
   \resumeItemListStart
   \resumeItem{Abstract : The hidden shift problem is defined over an unknown function $f$ and a hidden element $s$ that shifts the input of the function. Provided an oracle that can compute the function with and without the shift, the problem asks to recover $s$. One of the most remarkable cases is when $f$ is highly nonlinear, whereas best known classical algorithms take exponentially many oracle queries to retrieves. In particular, the hidden shift problem over maximally nonlinear Boolean functions (bent functions) reduces to the abelian hidden subgroup problem, or equivalently, the factorization problem. In this talk, we walk through two examples of quantum algorithms on the hidden shift problem over bent functions, namely the Roetteler’s and the Gavinsky’s algorithms which provide an exponential speedup compared to known classical algorithms. We show their implementation on quantum computers and address their impacts and limitations in the noisy-intermediate scale quantum era.}
   \resumeItemListEnd


    \resumeSubheadings
   {[2] Best Strategy for Malaria Eradication}{2021}
   {\small\textnormal{(Written in Korean, Co-authored with Minhyuk Seo, Sangwon Choi)}}{}
   {}{}
    \resumeItemListStart
   \resumeItem{Abstract : In this paper, we conduct both deterministic model and stochastic model of malaria infection. The former represents where the disease is pervasive, whereas the latter depicts where it newly prevails. We found that in the deterministic model, using both drug control and vector control with mid-intensity is economically optimal strategy to eradicate malaria infection. In stochastic model, there is no one absolute optimal strategy and therefore, additional case studies should be accompanied to find the best strategy.}\\
   \resumeItemListEnd


    \resumeSubheadings
   {[3] Heterogeneous Responses to Monetary Policy Shock in Industry Levels }{2020}
   {\textbf{and Responses of Equity Market : Case in Korea}}{}
   {}{}
    \resumeItemListStart
   \resumeItem{Abstract: This paper empirically studies the dynamic amongst monetary policy, output, and equity market in Korea. More specifically, it shows the heterogeneous responses of output in industry level to monetary policy shocks using Structural Vector Autoregression model. The study further examines whether equity market responds to monetary policy shock with respect to output changes. I find that industry sectors have different responses to monetary policy shocks in Korea, to which equity market does not react with respect to expected output changes.}\\
   \resumeItemListEnd

   \resumeSubHeadingListEnd
    \newpage
   
%   %-----------Publications-----------
%   \section{Publications}
%   \resumeSubHeadingListStart
%   \resumeItem{Kang H., Jung, Y., Park J., \emph{Fast Bayesian Functional Regression for Non-Gaussian Spatial Data}, In revision for \emph{Bayesian Analysis}}
%   %\resumeItem{Choi, M., Kim, D., Choi, E., Jung, Y., Choi, Y., Cho, J., Jeong, S., \emph{Mortality prediction of patients in intensive care units using machine learning algorithms with an electronic data extraction program}, Submitted to \emph{Critical Care Medicine}}
%   \resumeSubHeadingListEnd 

   %-----------presentation-----------
%   \section{Presentations}
%   \resumeSubHeadingListStart
%   \resumeItem{Gyeonghun Kang, Seonghyun Jeong \quotationmark{Generalized additive model via Bayesian model selection with mixtures of g-priors}. 2022 Korea Data Mining Society Conference. Aug 27, 2022. Pukyong University, Busan, Republic of Korea (Oral)}
%   \resumeItem{Gyeonghun Kang, Seonghyun Jeong \quotationmark{Generalized additive model via Bayesian model selection with mixtures of g-priors}. 2022 Brain Korea Academic Conference. June 30, 2022. Yonsei University, Seoul, Republic of Korea (Oral), \textbf{2nd Best Paper Awards}}
%   \resumeItem{Gyeonghun Kang, Seonghyun Jeong \quotationmark{Generalized additive model via Bayesian model selection}. Brain Korea Students Seminar. March 30, 2022. Yonsei University, Seoul, Republic of Korea (Oral)}
%   \resumeSubHeadingListEnd 
    
      %-----------Leadership and other academic ---------------
   \section{OTHER ACADEMIC EXPERIENCE}
   \resumeSubHeadingListStart
   \resumeSubheading{ \small\textnormal{(Director: Prof. Seung Ho Kang, Yonsei Univ.)} }{Sep 2021 -- Present}{Consultant}{Yonsei University}
   \resumeItemListStart
   \resumeItem{Provided advice on appropriate usage of statistical inference methods to researchers from diverse fields}
   \resumeItem{Headed the consultant team specialized in spatial modeling of geostatistical, areal and point pattern process data}
   
   \resumeItemListEnd
   \resumeSubheading{Essential Statistics Club (ESC) \small\textnormal{(Advisor: Prof. Jongho Im, Yonsei Univ.)} }{Sept 2019 -- June 2021}{Chief Instructor, Graduate Student Advisor}{Yonsei University}
   \resumeItemListStart
   \resumeItem{Led the team in employing Bayesian variable selection to US Crime data to win in-house data analysis competition}
   \resumeItem{Developed curriculum and course materials for \quotationmark{Introduction to Machine Learning}, posted online lectures on YouTube for members locked down due to COVID-19}
%   \resumeItem{Advised on constructing courses on Bayesian statistical methods and provided weekly session feedback}
   \resumeItemListEnd
   
   \resumeSubheading{Yonsei Investment Group (YIG) \small\textnormal{(Advisor: Prof. James Jinho Chang, Yonsei Univ.)}}{Sept 2017 -  Aug 2019}{Chief Instructor, Equity Fund Manager}{Yonsei University}
   \resumeItemListStart
   \resumeItem{Drafted and taught courses on portfolio management, corporate valuation and stock analysis}
   \resumeItem{Launched circa \$10K NAV equity fund investing in publicly traded stocks in South Korea}
   \resumeItemListEnd 
   \resumeSubHeadingListEnd
   %-----------Language Proficiency---------------
   \section{Standardized Tests}
%   Fluent in English and Native in Korean\\
   %IBT TOEFL : \textbf{120/120}: 30/30/30/30 (R/L/S/W) \\
   %GRE General Test :  \textbf{V 170} (99\%)/ \textbf{Q 170} (99\%)/ \textbf{W 4.0} (54\%) 
   IBT TOEFL : \textbf{114/120}: 30/30/25/29 (R/L/S/W) \\
   GRE General Test :  \textbf{V 164} (95\%)/ \textbf{Q 169} (93\%)/ \textbf{W 4.0} (54\%) 
   
 
   


   
   %\clearpage



   %-----------EXPERIENCE-----------
   \section{Teaching Experiences}
   \resumeSubHeadingListStart
   \resumeSubheading
   {Yonsei University}{Sep 2021 -- Present}
   {Teaching Assistant for Prof. Seonghyun Jeong}{}
   \resumeItemListStart
   \resumeItem{Statistical Computing (Undergraduate, Fall 2021, Fall 2022)}\\
   \resumeItem{Deep Learning with Python (Institute of Data Science summer/winter school, June, Aug 2021, Jan, May 2022)}\\
   \resumeItem{Bayesian Analysis with Stan (The Korean Statistical Society summer school, Aug 2022)}\\
   \resumeItemListEnd
%   \newpage
   \resumeSubheading
   {Youtube Channel}{Jan 2020 -- Present}
   {\url{www.youtube.com/c/HunLearning}}{}
   \resumeItemListStart
   \resumeItem{1.4K subscribers to date}\\
   \resumeItem{ Courses include \quotationmark{Bayesian Statistics} (English \& Korean, Feb 2021), \quotationmark{Mathematical Statistics explained} (Korean, Jan 2021), \quotationmark{Intuitive Linear Algebra} (Korean, Jan 2021), \quotationmark{Vector and Matrix Calculus} (Korean, Feb 2020), \quotationmark{Introduction to Machine Learning} (Korean, Jan 2020)}  \\
   \resumeItemListEnd
   
   \resumeSubHeadingListEnd
   
   

   
   
   
   %-----------PROGRAMMING SKILLS-----------
   \section{Programming Skills}
   \textbf{Advanced} R, Python \textbf{Moderate} MATLAB
   
   
   
   
   
   
   %-----------References---------------
   \section{References}
   \begin{tabular}{m{8cm} m{10cm}}
      \textbf{Seonghyun Jeong} & \\
      Assistant Professor & \\
      \vspace{1pt}
      Department of Applied Statistics & Phone: +82-02-2123-2521\\
      Yonsei University & Email: sjeong@yonsei.ac.kr
   \end{tabular}
   \vspace{10pt}
   
   \begin{tabular}{m{8cm} m{10cm}}
   \textbf{...} & \\
   ... & \\
   \vspace{1pt}
   ... & Phone: ...\\
   ... & Email: ...
   \end{tabular}
   \vspace{10pt}
   
   \begin{tabular}{m{8cm} m{10cm}}
      \textbf{...} & \\
      ... & \\
      \vspace{1pt}
      ... & Phone: ...\\
      ... & Email:...
   \end{tabular}
   
   
   
\end{document}
