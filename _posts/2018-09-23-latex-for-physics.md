---
title: LaTeX for Physics
layout: post
author: Jingying
permalink: /latex-physics/
description: physics latex
published: true
---
<div class="row">
<div class="6u 12u$(small)">
{% highlight tex %} 
	\documentclass{article}
	
	\usepackage[utf8]{inputenc}
	\title{Physics Cheat Sheet\\
		\small LaTeX for IB}
	\usepackage{graphicx}
	\usepackage[utf8]{inputenc}
	\usepackage{amssymb}
	\usepackage{hyperref}
	\usepackage[english]{babel}
	 \usepackage{graphicx}
	 \usepackage{amsmath}
	\newtheorem{theorem}{Theorem}
	\newtheorem{principle}{Principle}
	\newtheorem{cor}{Corollary}
	\graphicspath{{}}
	\setlength\parindent{24pt}
	\usepackage{indentfirst}
	
	% Start the document
	\begin{document}
	\author{Jingying}
	\maketitle{}
	
	
	% Create a new 1st level heading
	
	\section{Logistics}
	\subsection{List of Variables}
	\begin{enumerate}
		\item $s$ = distance; m
		\item $u$ = initial speed; m/s
		\item $v$ = final speed; m/s
		\item $a$ = acceleration; m/s$^{2}$
		\item $t$ = time; s; fundamental unit
		\item $J$ = joules; kgm$^{2}$s$^-2$
	\end{enumerate}
	
	\subsubsection{List of Constants}
	\begin{enumerate}
		\item $g$ = gravity; 9.81 m/s$^{2}$
	\end{enumerate}
	
	\subsection{Data Manipulation}
	\begin{list}{•}{}
		\item \textbf{Order of magnitude}: when rounding a number to its nearest power of 10, the cutoff value is \textbf{3.16}.
		\item \textbf{Significant Figures}: when \textbf{adding}, round to the largest (least significant figures) between two numbers. when \textbf{multiplying}, round to fewest significant digits.
		\item \textbf{Numerical constants} have perfect precision.
	\end{list}
	
	\subsection{Equations}
	\subsubsection{Error Propagation}
	Note: $\Delta x$ represents the uncertainty of x.
	\begin{enumerate}
		\item \textbf{Addition}: When $y=a+b$, $\Delta y = \Delta a + \Delta b$
		\item \textbf{Multiplication}: When $y=\dfrac{ab}{c}$, $\Delta y = y\times (\dfrac{\Delta a}{a}+ \dfrac{\Delta b}{b}+ \dfrac{\Delta c}{c})$.
		\item \textbf{Exponentiation}: When $y=a^{n}$, $\Delta y = y\times |n\dfrac{\Delta a}{a}|$.
	\end{enumerate}
	\section{Motion}
	
	\subsection{Terminology}
	\begin{enumerate}
		\item \textbf{Acceleration} is the change of \textit{velocity} over time.
		\item \textbf{Terminal velocity} is the constant speed that a freely falling object eventually reaches when the force of air resistance equals the force of gravity; the maximum velocity reached by an object.
		\item \textbf{Energy} is the potential to cause change and is measured in joules.
		\item \textbf{Projectile motion} is the motion of any object in free fall.
	\end{enumerate}
	
	\subsection{Principles}
	\begin{theorem} (Conservation of energy)
	Energy cannot be created nor destroyed.
	\end{theorem}
	
	\begin{cor} (Energy in a closed system)
	The sum of the initial energy equals the sum of the final energy in a closed system over time. 
	
	\begin{center}
	$\displaystyle \sum E_{i} = \sum E_{f}$
	\end{center}
	\end{cor}
	
	\begin{theorem} (lowest order of energy)
	All actions tend towards the lowest order of energy - internal energy, which is the heat energy of random movement of molecules.
	\end{theorem}
	
	\begin{theorem} (optimal launch angle)
	Ignoring air resistance, the optimal launch angle from rest on a plane surface is 45 for projectile motion that desires maximal range.
	\end{theorem}
	
	\subsection{Equations}
	\subsubsection{Energy}
	\begin{enumerate}
		\item $E_{k} = \dfrac{1}{2} m v^{2}$  Kinetic energy
		\item $E_{g} = m g h$  Gravitational potential energy 
	\end{enumerate}
	
	\subsubsection{One-Dimensional Linear Motion Equations}
	\begin{enumerate}
		\item $s = u+at$ From
		\item $v^{2}=u^{2}+2as$
		\item $s= \frac{(u+v)t}{2}$
		\item $s= ut+\dfrac{1}{2}at^{2}$
	\end{enumerate}
	\subsubsection{Projectile Motion in 1D}
	\begin{enumerate}
		\item $V_{0x}=V_{0} \cos \theta$ Initial horizontal velocity
		\item $V_{0y}=V_{0} \sin \theta$ Initial vertical velocity
		\item $x = V_{0x}t$ Range; horizontal displacement
		\item $\dfrac{V_{0y}^{2}}{2g}$  Maximum height reached
		\item $\dfrac{V_{0y}}{g}$ Time to maximum height
		\item $\dfrac{2V_{0y}}{g}$ Total time of flight
		
	\end{enumerate}
	
	\end{document}
{% endhighlight %}
</div>