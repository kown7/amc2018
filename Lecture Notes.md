---
title: "Lecture Notes: Architect's Master Class"
author: Kristoffer Nordström
header-includes: |
  \usepackage{hyperref}
  \usetheme[block=fill,progressbar=frametitle]{metropolis}
abstract: My summary of the AMC lectures in Stockholm 2018.
---

# Introduction

## Purpose and Outline

* Summary
    * Content Index
* Reference Sheet
* Showcase differences/3^rd^-party content

## Day 1

The Beating Will Continue Until Morale Improves


# The Architect

## Software Crisis

* Big Bullet Points \href[page=5]{Architects Master Class.pdf}{page 5 ff.}
    * Cost
    * Quality
    * Schedule
    * Staffing
    * Processes
* Software Engineering not a Degree (\href[page=10]{Architects Master Class.pdf}{p.~10.})
    * Terminology Inflation
	* *Code Molesters* called *Software Engineers*

You know it's bad when it has an [Wikipedia entry](https://en.wikipedia.org/wiki/Software_crisis).



## Architects


* Enterprise Architect (\href[page=13]{Architects Master Class.pdf}{p.~13.})
* Solution Architect (\href[page=14]{Architects Master Class.pdf}{p.~14.})
    * These slides
	* Project Lead (the hard part)
	* Architecture is easy
* \href[page=17]{Architects Master Class.pdf}{Technology}
* \href[page=17]{Architects Master Class.pdf}{Domain}
	* Developers not Technology and Design experts
	* Developers are Domain experts
	* Architects decouple the system



# Process Leadership

## \href[page=19]{Architects Master Class.pdf}{Objectives}

* Only small teams work, i.e. less than 7
* Avoid Cargo Cults
    * Steps
	* Tools
	* Techniques
* \href[page=19]{Architects Master Class.pdf}{Capability Maturity Model (CMM)}
    * CMM level 2--3, some 4
	* Most are at 1


## \href[page=22]{Architects Master Class.pdf}{Star(*)-ability}

Starability is a the word Juval uses to assemble all the words that match the `.*-ability` regular expression, e.g., scaleability.


## Minimum Cost Area

* \href[page=26]{Architects Master Class.pdf}{The cost for each service and the integration cost are non-linear curves}
* If not in the minimum cost area, throwing more people (linear) at the problem won't solve it.
* 25% of effort going to find minimum cost area
    * Hence Juval's *architect's greeting*

\begin{alertblock}{Non-Linearities}
Solving non linear problems with linear solutions is not working
\end{alertblock}


## Staffing

\href[page=22]{Architects Master Class.pdf}{p. 26 ff.}

* Architecture is larger risk than technology
* Ensure Design Integrity
* Context switches add at least a factor of 1.5 overhead
* Design is isomorphic to team interactions
     * Two-Way street
* \href[page=28]{Architects Master Class.pdf}{Core Team}

* Litmus Test for Architect Material
    * Hates the \emph{insanity} and waste
	* Doesn't have to spew out code like a torrent



## Development Plan (I)

* \href[page=29]{Architects Master Class.pdf}{Fuzzy Front End}
    * Important part with the core team to come to a Feed-Me/Kill-Me point.
    * Always provide options to Management
	* Mind the CLM
* \href[page=32]{Architects Master Class.pdf}{Staged Delivery}
* \href[page=34]{Architects Master Class.pdf}{\emph{Scope} and \emph{Effort} are inverted}
* \href[page=36]{Architects Master Class.pdf}{Services Integration Plan}
    * Integrate early (more features)
	* Milestones are integration points (not features)
	* *Never* base your progress report on features

## Development Plan (II)

\begin{alertblock}{Avoid Agile Mumbo-Jumbo}
\begin{itemize}
\item Design iteratively, build incrementally
\item Features are a result of integration, not part of the code (services/classes/functions)
\end{itemize}
\end{alertblock}


## \href[page=37]{Architects Master Class.pdf}{Service Life Cycle} | Development Plan (III)


\includegraphics[page=37,clip,trim=3.5cm 3.5cm 3.5cm 16cm, width=0.45\textwidth]{"Architects Master Class"}
\includegraphics[page=37,clip,trim=3.5cm 3.5cm 3.5cm 16cm, width=0.45\textwidth]{"Architects Master Class"}

Green: architect, yellow: senior developer, grey: developer. \href[page=95]{Architects Master Class.pdf}{Estimations}

Create V-Model equivalent


## \href[page=41]{Architects Master Class.pdf}{Estimations}

Avoid the CLM when giving estimations

* Yes; you're not going to make it
* *I don't know*; why are you here in the first place?
* any other; see above
* **Let me get back to you** $\Rightarrow$ create a project design.

Over- and underestimating are also CLM or worse.


* \href[page=43]{Architects Master Class.pdf}{Critical Path Analysis}
    * \href[page=49]{Architects Master Class.pdf}{Float Analysis}
* \href[page=51]{Architects Master Class.pdf}{Staffing Graphs}
* \href[page=57]{Architects Master Class.pdf}{Earned Value Planning}
    * Effort vs. Accomplishments
	* Make predictions
* \href[page=77]{Architects Master Class.pdf}{Roles of Architects and Project Managers}


## \href[page=77]{Architects Master Class.pdf}{Documentation}

* Excellence is in Documentation
    * Managers understand documentation, not code
* SDD



## \href[page=81]{Architects Master Class.pdf}{Requirement Management}

* Requirement are behavioural (not functional) $\Rightarrow$ Use-cases
    * *Nested if* can only be processed visually
* \href[page=83]{Architects Master Class.pdf}{Extensible Design}
    * Handle all requirements
	* Essence of agility
	* Handle bugs in requirements
* \href[page=84]{Architects Master Class.pdf}{Architecture Validation}
    * Minimal set of use-cases
* \href[page=90]{Architects Master Class.pdf}{Artificial Agility}
    * AI understands use-cases and generates code therefrom
	* c.f. \href[page=299]{Architects Master Class.pdf}{slide 86}, it's here.

\begin{alertblock}{Avoid Functional Decomposition}
Never design against the requirements!
\end{alertblock}


## Process Flow

Separation of \href[page=83]{Architects Master Class.pdf}{Business Architect vs.\ Software Architect}

\centering\href[page=83]{Architects Master Class.pdf}{\includegraphics[page=83,clip,trim=2.5cm 14cm 3.5cm 4cm, width=0.7\textwidth]{"Architects Master Class"}}


## \href[page=81]{Architects Master Class.pdf}{Hand-Off Point}

ballaballa

---

That's it, that's all.

\begin{exampleblock}{Example}
  \href[page=88]{Architects Master Class.pdf}{Will code for food!}
\end{exampleblock}


