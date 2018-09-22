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

<div class="6u 12u$(small)">
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>s</mi>
</mrow>
</math>
<!-- end MathToWeb --> = distance; m
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $u$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>u</mi>
</mrow>
</math>
<!-- end MathToWeb --> = initial speed; m/s
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $v$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>v</mi>
</mrow>
</math>
<!-- end MathToWeb --> = final speed; m/s
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $a$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>a</mi>
</mrow>
</math>
<!-- end MathToWeb --> = acceleration; m/s<!-- begin MathToWeb -->
<!-- (your LaTeX) $^{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msup>
		<mi></mi>
		<mn>2</mn>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $t$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>t</mi>
</mrow>
</math>
<!-- end MathToWeb --> = time; s; fundamental unit
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $J$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>J</mi>
</mrow>
</math>
<!-- end MathToWeb --> = joules; kgm<!-- begin MathToWeb -->
<!-- (your LaTeX) $^{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msup>
		<mi></mi>
		<mn>2</mn>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->s<!-- begin MathToWeb -->
<!-- (your LaTeX) $^-2$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msup>
		<mi></mi>
		<mn>-</mn>
	</msup>
	<mn>2</mn>
</mrow>
</math>
<!-- end MathToWeb -->
\end{enumerate}

\subsubsection{List of Constants}
\begin{enumerate}
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $g$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>g</mi>
</mrow>
</math>
<!-- end MathToWeb --> = gravity; 9.81 m/s<!-- begin MathToWeb -->
<!-- (your LaTeX) $^{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msup>
		<mi></mi>
		<mn>2</mn>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->
\end{enumerate}

\subsection{Data Manipulation}
\begin{list}{???}{}
	\item \textbf{Order of magnitude}: when rounding a number to its nearest power of 10, the cutoff value is \textbf{3.16}.
	\item \textbf{Significant Figures}: when \textbf{adding}, round to the largest (least significant figures) between two numbers. when \textbf{multiplying}, round to fewest significant digits.
	\item \textbf{Numerical constants} have perfect precision.
\end{list}

\subsection{Equations}
\subsubsection{Error Propagation}
Note: <!-- begin MathToWeb -->
<!-- (your LaTeX) $\Delta x$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>&#x00394;</mi>
	<mi>x</mi>
</mrow>
</math>
<!-- end MathToWeb --> represents the uncertainty of x.
\begin{enumerate}
	\item \textbf{Addition}: When <!-- begin MathToWeb -->
<!-- (your LaTeX) $y=a+b$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>y</mi>
	<mo>=</mo>
	<mi>a</mi>
	<mo>+</mo>
	<mi>b</mi>
</mrow>
</math>
<!-- end MathToWeb -->, <!-- begin MathToWeb -->
<!-- (your LaTeX) $\Delta y = \Delta a + \Delta b$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>&#x00394;</mi>
	<mi>y</mi>
	<mo>=</mo>
	<mi>&#x00394;</mi>
	<mi>a</mi>
	<mo>+</mo>
	<mi>&#x00394;</mi>
	<mi>b</mi>
</mrow>
</math>
<!-- end MathToWeb -->
	\item \textbf{Multiplication}: When <!-- begin MathToWeb -->
<!-- (your LaTeX) $y=\dfrac{ab}{c}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>y</mi>
	<mo>=</mo>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mrow>
					<mi>a</mi>
					<mi>b</mi>
				</mrow>
				<mi>c</mi>
			</mfrac>
		</mrow>
	</mstyle>
</mrow>
</math>
<!-- end MathToWeb -->, <!-- begin MathToWeb -->
<!-- (your LaTeX) $\Delta y = y\times (\dfrac{\Delta a}{a}+ \dfrac{\Delta b}{b}+ \dfrac{\Delta c}{c})$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>&#x00394;</mi>
	<mi>y</mi>
	<mo>=</mo>
	<mi>y</mi>
	<mo>&#x000D7;</mo>
	<mrow>
		<mo form="prefix">(</mo>
		<mstyle scriptlevel="0" displaystyle="true">
			<mrow>
				<mfrac linethickness="1">
					<mrow>
						<mi>&#x00394;</mi>
						<mi>a</mi>
					</mrow>
					<mi>a</mi>
				</mfrac>
			</mrow>
		</mstyle>
		<mo>+</mo>
		<mstyle scriptlevel="0" displaystyle="true">
			<mrow>
				<mfrac linethickness="1">
					<mrow>
						<mi>&#x00394;</mi>
						<mi>b</mi>
					</mrow>
					<mi>b</mi>
				</mfrac>
			</mrow>
		</mstyle>
		<mo>+</mo>
		<mstyle scriptlevel="0" displaystyle="true">
			<mrow>
				<mfrac linethickness="1">
					<mrow>
						<mi>&#x00394;</mi>
						<mi>c</mi>
					</mrow>
					<mi>c</mi>
				</mfrac>
			</mrow>
		</mstyle>
		<mo form="postfix">)</mo>
	</mrow>
</mrow>
</math>
<!-- end MathToWeb -->.
	\item \textbf{Exponentiation}: When <!-- begin MathToWeb -->
<!-- (your LaTeX) $y=a^{n}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>y</mi>
	<mo>=</mo>
	<msup>
		<mi>a</mi>
		<mi>n</mi>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->, <!-- begin MathToWeb -->
<!-- (your LaTeX) $\Delta y = y\times |n\dfrac{\Delta a}{a}|$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>&#x00394;</mi>
	<mi>y</mi>
	<mo>=</mo>
	<mi>y</mi>
	<mo>&#x000D7;</mo>
	<mo>|</mo>
	<mi>n</mi>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mrow>
					<mi>&#x00394;</mi>
					<mi>a</mi>
				</mrow>
				<mi>a</mi>
			</mfrac>
		</mrow>
	</mstyle>
	<mo>|</mo>
</mrow>
</math>
<!-- end MathToWeb -->.
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
<!-- begin MathToWeb -->
<!-- (your LaTeX) $\displaystyle \sum E_{i} = \sum E_{f}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mstyle displaystyle="true">
		<mstyle displaystyle="true">
			<mo>&#x02211;</mo>
		</mstyle>
		<msub>
			<mi>E</mi>
			<mi>i</mi>
		</msub>
		<mo>=</mo>
		<mstyle displaystyle="true">
			<mo>&#x02211;</mo>
		</mstyle>
		<msub>
			<mi>E</mi>
			<mi>f</mi>
		</msub>
	</mstyle>
</mrow>
</math>
<!-- end MathToWeb -->
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
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $E_{k} = \dfrac{1}{2} m v^{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msub>
		<mi>E</mi>
		<mi>k</mi>
	</msub>
	<mo>=</mo>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mn>1</mn>
				<mn>2</mn>
			</mfrac>
		</mrow>
	</mstyle>
	<mi>m</mi>
	<msup>
		<mi>v</mi>
		<mn>2</mn>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->  Kinetic energy
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $E_{g} = m g h$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msub>
		<mi>E</mi>
		<mi>g</mi>
	</msub>
	<mo>=</mo>
	<mi>m</mi>
	<mi>g</mi>
	<mi>h</mi>
</mrow>
</math>
<!-- end MathToWeb -->  Gravitational potential energy 
\end{enumerate}

\subsubsection{One-Dimensional Linear Motion Equations}
\begin{enumerate}
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $s = u+at$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>s</mi>
	<mo>=</mo>
	<mi>u</mi>
	<mo>+</mo>
	<mi>a</mi>
	<mi>t</mi>
</mrow>
</math>
<!-- end MathToWeb --> From
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $v^{2}=u^{2}+2as$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msup>
		<mi>v</mi>
		<mn>2</mn>
	</msup>
	<mo>=</mo>
	<msup>
		<mi>u</mi>
		<mn>2</mn>
	</msup>
	<mo>+</mo>
	<mn>2</mn>
	<mi>a</mi>
	<mi>s</mi>
</mrow>
</math>
<!-- end MathToWeb -->
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $s= \frac{(u+v)t}{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>s</mi>
	<mo>=</mo>
	<mfrac linethickness="1">
		<mrow>
			<mrow>
				<mo form="prefix">(</mo>
				<mi>u</mi>
				<mo>+</mo>
				<mi>v</mi>
				<mo form="postfix">)</mo>
			</mrow>
			<mi>t</mi>
		</mrow>
		<mn>2</mn>
	</mfrac>
</mrow>
</math>
<!-- end MathToWeb -->
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $s= ut+\dfrac{1}{2}at^{2}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>s</mi>
	<mo>=</mo>
	<mi>u</mi>
	<mi>t</mi>
	<mo>+</mo>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mn>1</mn>
				<mn>2</mn>
			</mfrac>
		</mrow>
	</mstyle>
	<mi>a</mi>
	<msup>
		<mi>t</mi>
		<mn>2</mn>
	</msup>
</mrow>
</math>
<!-- end MathToWeb -->
\end{enumerate}
\subsubsection{Projectile Motion in 1D}
\begin{enumerate}
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $V_{0x}=V_{0} \cos \theta$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msub>
		<mi>V</mi>
		<mrow>
			<mn>0</mn>
			<mi>x</mi>
		</mrow>
	</msub>
	<mo>=</mo>
	<msub>
		<mi>V</mi>
		<mn>0</mn>
	</msub>
	<mi>cos</mi>
	<mi>&#x003B8;</mi>
</mrow>
</math>
<!-- end MathToWeb --> Initial horizontal velocity
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $V_{0y}=V_{0} \sin \theta$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<msub>
		<mi>V</mi>
		<mrow>
			<mn>0</mn>
			<mi>y</mi>
		</mrow>
	</msub>
	<mo>=</mo>
	<msub>
		<mi>V</mi>
		<mn>0</mn>
	</msub>
	<mi>sin</mi>
	<mi>&#x003B8;</mi>
</mrow>
</math>
<!-- end MathToWeb --> Initial vertical velocity
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $x = V_{0x}t$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mi>x</mi>
	<mo>=</mo>
	<msub>
		<mi>V</mi>
		<mrow>
			<mn>0</mn>
			<mi>x</mi>
		</mrow>
	</msub>
	<mi>t</mi>
</mrow>
</math>
<!-- end MathToWeb --> Range; horizontal displacement
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $\dfrac{V_{0y}^{2}}{2g}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mrow>
					<msubsup>
						<mi>V</mi>
						<mrow>
							<mn>0</mn>
							<mi>y</mi>
						</mrow>
						<mn>2</mn>
					</msubsup>
				</mrow>
				<mrow>
					<mn>2</mn>
					<mi>g</mi>
				</mrow>
			</mfrac>
		</mrow>
	</mstyle>
</mrow>
</math>
<!-- end MathToWeb -->  Maximum height reached
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $\dfrac{V_{0y}}{g}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mrow>
					<msub>
						<mi>V</mi>
						<mrow>
							<mn>0</mn>
							<mi>y</mi>
						</mrow>
					</msub>
				</mrow>
				<mi>g</mi>
			</mfrac>
		</mrow>
	</mstyle>
</mrow>
</math>
<!-- end MathToWeb --> Time to maximum height
	\item <!-- begin MathToWeb -->
<!-- (your LaTeX) $\dfrac{2V_{0y}}{g}$ -->
<math xmlns="http://www.w3.org/1998/Math/MathML">
<mrow>
	<mstyle scriptlevel="0" displaystyle="true">
		<mrow>
			<mfrac linethickness="1">
				<mrow>
					<mn>2</mn>
					<msub>
						<mi>V</mi>
						<mrow>
							<mn>0</mn>
							<mi>y</mi>
						</mrow>
					</msub>
				</mrow>
				<mi>g</mi>
			</mfrac>
		</mrow>
	</mstyle>
</mrow>
</math>
<!-- end MathToWeb --> Total time of flight
	
\end{enumerate}


<!-- % Uncomment the following two lines if you want to have a bibliography. Please do not forget to add an entry to your bibliography and reference it by using the \cite{} command -->
<!-- %\bibliographystyle{alphadin} -->
<!-- %\bibliography{document} -->
</div>