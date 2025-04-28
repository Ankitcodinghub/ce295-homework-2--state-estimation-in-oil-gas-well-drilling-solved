# ce295-homework-2--state-estimation-in-oil-gas-well-drilling-solved
**TO GET THIS SOLUTION VISIT:** [CE295 Homework 2- State Estimation in Oil & Gas Well Drilling Solved](https://www.ankitcodinghub.com/product/ce295-hw-2-state-estimation-in-oil-gas-well-drilling-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119339&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE295 Homework 2- State Estimation in Oil \u0026amp; Gas Well Drilling Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
“The Armageddon Movie Problem”

This assignment provides you with hands-on practice for state estimation, with application to oil &amp; gas energy systems. The assignment is organized in a tutorial fashion, thereby allowing you to practice state estimation on a relevant real-world energy system example.

Movie-goers will recognize this problem from the 1998 science fiction thriller “Armageddon.” In this movie, Bruce Willis, an experienced and gritty offshore oil-driller, must drill a hole into an asteroid plummeting towards Earth to destroy it. If only he knew about state estimation, then maybe he could prevent the insufferable Ben Affleck from marrying Liv Tyler… and save Earth.

Reading

The following four articles on bCourses describe state estimation in various energy applications: batteries [2], buildings [3], traffic [4], and geophysical systems [5]. Please peruse for your own self-interest. There are no questions regarding this reading.

Background

The process of oil well drilling involves creating a borehole several thousand meters deep in the ground until an oil reservoir is reached. The drill string, consisting of the assembly of drill pipes, drill collars, and the rock-cutting tool referred to as drill bit (see

Figure 1) rotates around its vertical axis, penetrating through the rock. At the top of the drillstring, Figure 1: Schematic view of a drilling system [1]. the rotary table provides the necessary torque to put the system into a rotational motion.

During this process, the downhole drill bit will stick and slip, causing oscillations in the drill string and creating mechanical fatigue to the bit itself. For this reason, it is crucial to monitor the drill bit speed. However, it’s nearly impossible to place sensors thousands of meters into the ground, especially in the perilous environment near the bit which contains flows of rock cuttings, oil, gas, water, and mud. For this reason, we seek to estimate the bit velocity by fusing a model of the drill string dynamics, and measurements of the rotary table speed.

Problem 1: Dynamic System Modeling

We model the drill-string as two rigid rotating bodies: the table/top portion and the bit/bottom portion, connected by a rotational spring, as shown in Fig. 2. The top and bottom have rotational inertia JT and JB, respectively. An electric

motor provides the table torque T(t). The rock provides some Viscous

unmeasurable frictional torque Tf(t) on the drill bit at the Drag

bottom. The top and bottom also experience torques from

viscous drag and the rotational spring. Table/Top

Rotational Inertia

(a). Define &amp; write the modeling objective. What are the controllable and uncontrollable inputs? What are the measured and performance outputs? List the parameters.

(b). Use Newton’s second law in rotational coordinates to de- Viscous rive the equations of motion for the top/table and bot- Drag tom/bit portions of the drill string. HINT: Fig 2 is a free Bit/Bottom

body diagram. Rotational Inertia

(c). Write all the dynamical equations into matrix state space

form. What are the A,B,C matrices? Hint: A ∈R4×4. T (t), Frictional Torque

Figure 2: Free-body diagram of drill string. Problem 2: Observability Analysis

In this problem, we consider IF it’s possible to estimate the bit velocity from table velocity measurements.

Assume the following parameter values: JT = 100,JB = 25,k = 2,b = 5.

(a). Compute the Observability Matrix O described in Section 2 of Chapter 2, and include in your submitted report. Are all the states observable from measurements of table velocity? Justify why or why not.

(b). Define a new state θ(t) = θT(t)−θB(t) as the relative angular displacement between the top and bottom. Re-derive the state-space model replacing θT,θB with θ only. Provide the new A,B,C matrices.

(c). Compute the Observability Matrix O for this modified model, and include in your report. Is the bit velocity observable from measurements of the table velocity? Justify why or why not.

Problem 3: Measurement Data Download HW2_Skeleton.m/HW2_Skeleton.ipynb and HW2_Data.csv from bCourses. Import HW2_Data.csv. In one figure, with two subplots, plot the table torque T(t) and measured table velocity ωT(t) versus time. Use legends, x- and y-labels, appropriate font sizes, and line widths. Provide the plot in your report.

Problem 4: Luenberger Observer

In this problem we design a Luenberger observer to estimate bit speed from the 3-state model and measurements. You are encouraged to experiment with the eigenvalue placement to obtain a good balance between estimation speed and robustness to noise.

(a). Compute the eigenvalues of the open loop system, A. Write down the Luenberger observer equations in your report.

(b). Design the output error injection gain, L, as described in Chapter 2, Section 3. Select some desired eigenvalues for the error system matrix (A − LC). Remember, the only requirements are that (i) the real parts must be strictly negative (Re[λi(A − LC)] &lt; 0,∀ i), and (ii) complex numbers must be in complex conjugate pairs. Provide your selected eigenvalues and observer gain L in the report. Justify your choice of eigenvalues. HINT: You need the place and acker commands in Matlab and Python, respectively. These require the Matlab Control Systems Toolbox or Python Control Systems module.

(c). Write down the state-space matrices for your Luenberger observer, denoted Alobs,Blobs,Clobs. Note, the frictional torque is unknown and unmeasured and therefore not included in the Luenberger observer.

(d). In one figure, create two subplots. On top, plot the estimated bit speed ωˆB(t) versus the true value omega_B_true from HW2_Data.csv. On bottom, plot the estimation error ωB(t) − ωˆB(t). Compute the root mean square error (RMSE), given by:

(1)

where T is the total simulation time, i.e. t ∈ [0,T]. Use these plots and the RMSE to tune the eigenvalues of (A − LC). Provide this plot in your report, and document your eigenvalue placement for (A − LC). HINT: There is no single best answer. Tune to your preference.

Problem 5: Kalman Filter (KF) Design

In this problem we design a Kalman Filter, using the canonical model format

x˙(t) = Ax(t) + Bu(t) + Bww(t), (2)

ym(t) = Cx(t) + n(t), (3)

where x(t) = [θ(t),ωT(t),ωB(t)], u(t) = T(t), w(t) = Tf(t), and ym(t) = ωT(t) + n(t). The process noise w(t) encapsulates unknown frictional torque on the drill bit. The measurement noise n(t) represents noise in the table velocity sensor ωT(t).

(a). Write down the Kalman filter equations from Chapter 2, Section 4.

(b). Implement the Kalman filter equations in your code. Assume the measurement noise covariance is

N = 0.02, the mean initial condition is x0 = 03×1, and the initial condition covariance is Σ0 = I3×3. Tune the process noise covariance W ∈R3×3, and provide the value in your report. Explain how you tuned covariance matrix W.

(c). In one figure, create two subplots. On top, plot the estimated bit speed ωˆB(t) versus the true value omega_B_true from HW2_Data.csv. Also plot the ± one-standard deviation bound, i.e. ωˆB(t) ± pΣ3,3(t). On bottom, plot the estimation error ωB(t) − ωˆB(t). Use these plots to tune the process covariance W. Provide this plot in your report.

(d). Compute the eigenvalues of A − L(t)C, where t is the final time of 300 sec. How does this compare to your pole placement in the Luenberger observer? FOR FUN (ungraded): Generate an animated plot of the λi(A − L(t)C) on the real-complex plane. Watch the eigenvalues move.

Problem 6: Extended Kalman Filter (EKF) Design

Now we consider a nonlinear rotational spring law. In Fig. 2 and Problem 1, we relate spring displacement θ(t) and spring torque by Hooke’s law: kθ(t). This is a linear relationship. In reality, spring torque exhibits a nonlinear relationship. In this problem, let us replace Hooke’s law with the more realistic nonlinear spring torque relationship: k1θ(t) + k2θ3(t). Consider values of k1 = 2 and k2 = 0.25.

Design and implement an Extended Kalman Filter from CH2, Section 5 by copying, pasting, and modifying your KF code. Use the covariance W you used from Problem 5. In your report:

• Derive expressions for the Jacobians: .

• Write down the EKF equations.

• In one figure, create two subplots like Problem 5. On top, plot the estimated bit speed ωˆB(t) versus the true value omega_B_true from HW2_Data.csv. Compute the RMSE. Also plot the ± one-standard

deviation bound, i.e. ωˆB(t) ±pΣ3,3(t). On bottom, plot the estimation error ωB(t) − ωˆB(t).

Deliverables

Submit the following on bCourses. Be sure that the function files are named exactly as specified (including spelling and case). Please do NOT zip files.

LASTNAME_FIRSTNAME_HW2.PDF

LASTNAME_FIRSTNAME_HW2.xyz which contains your respective Matlab or Python files, i.e. xyz∈{m, ipynb}.

References

[3] P. Radecki and B. Hencey, “Online building thermal parameter estimation via unscented kalman filtering,” in 2012 American Control Conference (ACC), 2012, pp. 3056–3062.

[4] D. Work, O.-P. Tossavainen, S. Blandin, A. Bayen, T. Iwuchukwu, and K. Tracton, “An ensemble kalman filtering approach to highway traffic estimation using gps enabled mobile devices,” in 47th IEEE Conference on Decision and Control, Dec 2008, pp. 5062–5068.
