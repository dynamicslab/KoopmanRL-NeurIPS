---
layout: default
title: Koopman-Assisted Reinforcement Learning
---


## Abstract

The Bellman equation and its continuous form, the Hamilton-Jacobi-Bellman (HJB) equation, are ubiquitous in reinforcement learning (RL) and control theory contexts due, in part, to their guaranteed convergence towards a system’s optimal value function. However, this approach has severe limitations. This paper explores the connection between the data-driven Koopman operator and Bellman Markov Decision Processes, resulting in the development of two new RL algorithms to address these limitations. In particular, we focus on Koopman operator methods that reformulate a nonlinear system by lifting into new coordinates where the dynamics become linear, and where HJB-based methods are more tractable. These transformations enable the estimation, prediction, and control of strongly nonlinear dynamics. Viewing the Bellman equation as a controlled dynamical system, the Koopman operator is able to capture the expectation of the time evolution of the value function in the given systems via linear dynamics in the lifted coordinates. By parameterizing the Koopman operator with the control actions, we construct a new _Koopman tensor_ that facilitates the estimation of the optimal value function. Then, a transformation of Bellman’s framework in terms of the Koopman tensor enables us to reformulate two max-entropy RL algorithms: soft-value iteration and soft actor-critic (SAC). This highly flexible framework can be used for deterministic or stochastic systems as well as for discrete or continuous-time dynamics. Finally, we show that these algorithms attain state-of-the-art (SOTA) performance with respect to traditional neural network-based SAC and linear quadratic regulator (LQR) baselines on three controlled dynamical systems: the Lorenz system, fluid flow past a cylinder, and a double-well potential with non-isotropic stochastic forcing. It does this all while maintaining an interpretability that shows how inputs tend to affect outputs, what we call _input-output_ interpretability.

## The Different Aspects of the Dataset Visualized

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)


## Authors

<center>
<div class="row1">
    <div style="float:left;margin-right:20px;">
        <img src="rozwood.png" height="200" width="200" alt="preston" />
        <p style="text-align:center;"><a href="https://github.com/Pdbz199">Preston Rozwood</a></p>
    </div>
    <div style="float:left;margin-right:20px;">
        <img class="middle-img" src="mehrez.jpg" height="200" width="200" alt="ludger" />
        <p style="text-align:center;"><a href="https://www.linkedin.com/in/edward-mehrez-aa316082">Edward Mehrez</a></p>
    </div>
</div>
 </center>

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

<div class="row2">
    <center>
    <div style="float:left;margin-right:20px;">
        <img src="paehler.png" height="200" width="200" alt="tal" />
        <p style="text-align:center;"><a href="https://ludger.fyi">Ludger Paehler</a></p>
    </div>
    <div style="float:left;margin-right:20px;">
        <img class="middle-img" src="sun.png" height="200" width="200" alt="jacob" />
        <p style="text-align:center;"><a href="https://wensun.github.io">Wen Sun</a></p>
    </div>
    <div style="float:left;margin-right:20px;">
        <img src="brunton.png" height="200" width="200" alt="william" />
        <p style="text-align:center;"><a href="https://www.eigensteve.com">Steven L. Brunton</a></p>
    </div>
    </center>
</div>

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>


## Corresponding Authors

* Preston Rozwood ([pwr36@cornell.edu](mailto:pwr36@cornell.edu?subject=KARL))
* Edward Mehrez ([ejm322@cornell.edu](mailto:ejm322@cornell.edu?subject=KARL))

## Citation

```bibtex
@inproceedings{rozwood2023koopman,
  title={Koopman-Assisted Reinforcement Learning},
  author={Rozwood, Preston and Mehrez, Edward and Paehler, Ludger
          and Sun, Wen and Brunton, Steven},
  booktitle={NeurIPS 2023 AI for Science Workshop},
  year={2023}
}
```
