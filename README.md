# complex-systems-project-1-elementary-cellular-automata-solved
**TO GET THIS SOLUTION VISIT:** [Complex-Systems Project 1-Elementary Cellular Automata Solved](https://www.ankitcodinghub.com/product/complex-systems-project-1-elementary-cellular-automata-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95180&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Complex-Systems Project 1-Elementary Cellular Automata Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
PART I: Diploid Cellular Automata

1.1 Framework and definition of diploid CA

</div>
<div class="column">
Project 1

</div>
</div>
<div class="layoutArea">
<div class="column">
In elementary cellular automata (ECA) all cells are updated synchronously so that the state of each cell is updated according to the state of the cell itself and to that of the two neighboring cells. The set of these three cells will be called neighborhood of a given cell. More precisely, given a local rule f, we denote by F : Xn → Xn the map defined by letting

(F(x))i = f(xi−1,xi,xi+1)

for any cell i. The Elementary Cellular Automata (ECA) associated with the local rule f is the collection of all the sequences of configurations (xt)t∈N obtained by applying the map F iteratively, namely, such that xt = F(xt−1). The particular sequence (xt)t∈N such that x0 = x ∈ Xn is called trajectory of the cellular automaton associated with the initial condition x.

Each of the possible 256 local rules f is identified by the integer number W ∈ {0,…,255} such that

W =f(0,0,0)·20 +f(0,0,1)·21 +f(0,1,0)·22 +f(0,1,1)·23 +···+f(1,1,1)·27 that is to say the collection of the digits

f(1, 1, 1)f(1, 1, 0)f(1, 0, 1)f(1, 0, 0)f(0, 1, 1)f(0, 1, 0)f(0, 0, 1)f(0, 0, 0)

is the binary representation of the number W.

Some examples. The rule 0 is called the null rule and associates the state 0 to any

configuration in the neighborhood. The rule 22 associates the state 0 to any configuration in the neighborhood but for the three local configurations in which one single 1 is present in the neighborhood (001, 010, and 100) to which it associates 1. The rule 150 associates the state 0 to any configuration in the neighborhood but for the four local configurations in which an odd number of 1’s is present in the neighborhood (001, 010, 100, and 111) to which it associates 1. The rule 204 is called the identity and associates to any configuration in the neighborhood the state of the cell at the center (namely, the cell that one is going to update). The rule 224 associates the state 1 to any configuration in

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
the neighborhood but for the local configuration 000 to which it associates 0. The rule 232 is called the majority rule and associates to any configuration in the neighborhood the majority state, namely 0 to 000, 001, 010, and 100 and 1 to the others. The rule 255 associates the state 1 to any configuration in the neighborhood. Finally, note that all the rules represented by an even number associated to the local configuration 000 the states 0.

In this context a Probabilistic Cellular Automata, called probabilistic or stochastic ECA, is a Markov chain (ξt)t∈N on the configuration space Xn with transition matrix

p(x, y) = 􏰇 pi(yi|x) with pi(yi|x) = yiφ(xi−1, xi, xi+1) + (1 − yi)[1 − φ(xi−1, xi, xi+1)] i∈Ln

(1) where φ has to be interpreted as the probability to set the cell to 1 given the neighborhood xi−1xixi+1 and, similarly, 1−φ the probability select 0. We denote by Px the probability associated with the process started at x ∈ Xn. We shall denote by μxt (y) = Px(ξt = y) the probability that the chain started at x will be in the configuration y at time t. Abusing the notation, μxt (Y ) = Px(ξt ∈ Y ) will denote the probability that the chain

started at x will be in the set of configurations Y ⊂ Xn at time t.

An important class of stochastic ECA is made of those models obtained by randomly

mixing two of the 256 elementary cellular automata. More precisely, given λ ∈ (0, 1) and picked two local rules f1 ̸= f2, the stochastic ECA defined by

φ = (1−λ)f1 +λf2 (2)

is called a diploid ECA. Note that in the limiting cases λ = 0, 1 or f1 = f2 a (determin- istic) ECA is recovered.

It is important to note that the time evolution of the diploid ECA can be described as follows: at time t for each cell i one chooses either the rule f1 with probability 1 − λ or the rule f2 with probability λ and performs the updating based on the neighborhood configuration at time t − 1. Indeed, with this algorithm the probability to set the cell to1atimetis0iff1 =0andf2 =0(wherethelocalrulesarecomputedinthe neighborhood configuration at time t−1), 1−λ if f1 = 1 and f2 = 0, λ if f1 = 0 and f2 = 1, 1 if f1 = 1 and f2 = 1, which is coherent with the definition (2).

1.2 The project

We start trying to simulate diploid ECA of the type:

φ = (1−λ)f1 +λf2

Here, we focus on models in which f1 is the null rule (i.e. rule 0) and f2 is any other

rule in the following list:

F2 := { 18,22,26,28,30,50,54,58,60,62,78,90,94,110, 122, 126, 146, 150, 154, 156, 158, 178, 182, 186, 188, 190, 202, 206, 218, 234, 238, 250, 254}

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1.3 Simulation Studies

<ul>
<li>choose two rules f2 from F2 and repeat the simulation study explained below for each of them.</li>
<li>The number of cells is set to n = 104.</li>
<li>As initial condition a configuration in which cells are populated with zeros or ones
with equal probability
</li>
<li>The diploid is let evolve for the time T = 5 · 103.</li>
<li>In the final configuration the fraction of cells set to 1, called density, is computed.</li>
<li>QUESTION: is this number an estimate of the averaged density along an infinite long run of the diploid in the infinite volume limit n → ∞?</li>
<li>Try to estimate the curve of the density in function of the parameter λ, trying to be more accurate around the points where you notice a change of behavior. For instance increase λ by step of 0.05 and then by steps of 0.01 near the sudden change of density.</li>
<li>QUESTION: critically study the behaviour of the density.</li>
<li>QUESTION: is there any abrupt change of behavior?</li>
<li>QUESTION: do you think, from the indication of your plot that the system has a phase transition in λ (e.g. first or second order)?</li>
<li>QUESTION: if yes, is there any indication of the presence of any critical λ?</li>
<li>QUESTION: if you look carefully at the list F, you might notice that it contains only even rules. What do you think would happen heuristically in case of an odd f2 rule?</li>
</ul>
1.4 Theoretical study (f2 is rule 204)

Consider the diploid with f2 being the rule 255. Each cell is updated independently on the others and also on the past. Hence, the evolution of a cell amounts to be a sequence of Bernoulli variables with parameter λ. Thus, the invariant measure of the chain is product and for each cell it is equal to πi(0) = 1 − λ and πi(1) = λ.

Consider now the diploid with f2 being the identity (rule 204). For this model the configuration 0 is a fixed point (also called stationary state ), in the sense that p(0, x) = 0 for any x ∈ Xn. The cells are updated independently one from each other but not on the past. The chain can be described as a collection of n single cell Markov chains evolving with the following transition matrix

pi(0,0)=1, pi(0,1)=0, pi(1,0)=1−λ, pi(1,1)=λ.

for any cell i. The stationary measure is product and the single cell stationary measure

is concentrated on 0, namely, πi(0) = 1 and πi(1) = 0. 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>QUESTION: For a single cell started at 1, calculate the probability that its state is0attimet. Fortheallchainshowthatμ1t(0)=(1−λt)n.</li>
<li>QUESTION: Try to obtain the probability of reaching at time t the configuration with all zeros if started in the configuration with all ones (μ1t (0)) of the previous point by using the multinomial theorem. In fact, one can rewrite the probability as sum over all the ways in which 1’s are removed once we know that 􏰆tk=1 sk = n, where sk is the number of ones removed at time k.</li>
<li>QUESTION: Now, suppose to compute this probability on a time scale diverging logarithmically with n, namely, take t = αlogn, for some α &gt; 0. Show that, for any λ ∈ (0,1), if α &lt; −1/logλ then μ1t(0) tends to 0 in the infinite volume limit, whereas it tends to 1 if α &gt; −1/logλ.</li>
<li>For this simple model you have showed that: fixed λ on a time scale smaller than (−1/ log λ) log n the chain started at 1 stays in 1. On a time scale larger than (−1/ log λ) log n it converges to the configuration 0. Note that in this model this happens for any value of λ. This suggests that in the other models, something similar is observed but only for λ small enough.</li>
<li>QUESTION: Despite rule 204 is not in the list F2, does this heuristics shed some light on what it is going on? Come back to the simulation studies you have performed. The previous observation is consistent with what you have observed?</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
PART II

You have to choose and solve only one of the following two projects: Asynchronous CA or Explicit solution of a CA described in the following sections.

2.1 Asynchronous CA

This part of the project would like to investigate the robustness of CA to asynchronous updating via the so called α − asynchronous dynamics. In this dynamics we apply a local rule f with a probability α (the synchrony rate) or we keep the same state with a probability 1 − α, independently for each cell. Note that by taking α = 1, we recover the synchronous case (i.e. parallel updating) and as α is decreased, the update rule becomes more asynchronous.

In the context of ECA, an α − asynchronous dynamics can be written as a diploid ECA as:

φ=αf1 +(1−α)f2 (3) with f2 being the rule 204 (identity rule!).

</div>
</div>
<div class="layoutArea">
<div class="column">
•

•

2.2

</div>
<div class="column">
QUESTION: consider now the thee α − asynchronous dynamics, when f1 ∈ {6, 50, 178}. With simulation parameters similar to the Simulation Studies, draw (part of) the space time diagrams with α = 0.25, α = 0.50 and α = 0.75, starting from a random initial configuration. What do you observe? How does qualitatively change the approach to the equilibrium as α increases?

QUESTION: try to estimate the curve of the equilibrium density in function of the parameter α, for f1 ∈ {6, 50}. Are there any critical value of α? Try to give an heuristic explanation of what you observe, underline the differences between the two ECA.

Explicit solution of a CA

</div>
</div>
<div class="layoutArea">
<div class="column">
This part of the project would like to investigate the solution of a ECA in terms of its initial condition. In particular we will focus on ECA 172.

<ul>
<li>QUESTION: Starting from a configuration in which cells are populated with zeros or ones with equal probability, draw part of a time-space diagram and try to assess to which Wolfram class the ECA 172 belongs.</li>
<li>QUESTION: Try to inspect the fate of clusters of two or more zeroes and of isolated zeros.</li>
<li>We consider now an infinite ECA 172, i.e., defined in all Z. We denote with x the initial condition x ∈ {0,1}Z and we study [Fn(x)]0, i.e., the value at the origin after n iteration of the CA. One can indeed proves that:
􏰄n−3 􏰅

[F n(x)]0 = x ̄−2x ̄−1×0 + 􏰇 (1 − x ̄ix ̄i+1) (x ̄n−2xn−1 − xn−2xn) (4)

i=−2

where we used the notation x ̄i := 1 − xi, for i ∈ Z.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<ul>
<li>QUESTION: Derive the solution for [Fn(x)]j for any j ∈ Z.</li>
<li>The initial configuration is now a random configuration, sampled from a Bernoulli distribution with parameter p. More precisely, let xj = Xj for j ∈ Z, where Xj are independent and identically distributed random variables such that P(Xj = 1) = q, where q ∈ (0, 1).</li>
<li>It can be proven (BONUS: prove it, but it is not trivial!!!) that the expectation with respect to the Bernoulli product measure is:</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
E

</div>
<div class="column">
􏰄n−1 􏰅q

􏰇(1 − X ̄iX ̄i+1) = (γ1λn−2 + γ2λn−2) (5)

</div>
</div>
<div class="layoutArea">
<div class="column">
with

</div>
<div class="column">
i=1 λ2−λ112 λ1,2 := 1q ± 1􏰈q(4 − 3q),

</div>
</div>
<div class="layoutArea">
<div class="column">
22

􏰀q 􏰁􏰈 􏰂q2 􏰃 γ1,2:= 2−1 q(4−3q)± 2−1

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>QUESTION: By using (5), calculate E([Fn(X)]0) and E([Fn(X)]j). Are they equal?</li>
<li>QUESTION: Calculate the limit:

lim E([Fn(X)]j)

n→∞

and try to relate it to the asymptotic density of ones of ECA 172. If you look back at the space-time diagram you have drawn, what you can say about the asymptotic configuration?
</li>
<li>CURIOSITY: In case q = 21 ,

E([Fn(X)]j) = 1 + Fn+3</li>
</ul>
8 2n+2

where Fn is the n-th Fibonacci number.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
