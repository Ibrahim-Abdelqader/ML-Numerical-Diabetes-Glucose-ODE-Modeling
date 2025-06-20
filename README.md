# ML-Numerical-Diabetes-Glucose-ODE-Modeling

<p align="center">
  <a href="" rel="noopener">
    



</p>
<p align="center">
    <br> 
</p>
<div align="center">

[![GitHub contributors](https://img.shields.io/github/contributors/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling)](https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling/contributors)
[![GitHub issues](https://img.shields.io/github/issues/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling)](https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling/issues)
[![GitHub forks](https://img.shields.io/github/forks/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling)](https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling/network)
[![GitHub stars](https://img.shields.io/github/stars/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling)](https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling/stargazers)
[![GitHub license](https://img.shields.io/github/license/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling)](https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling/blob/main/LICENSE)

</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About The Project</a>
      <ul>
        <li><a href="#tech">Built Using</a></li>
      </ul>
    </li>
    <li>
      <a href="#install">Getting Started</a>
      <ul>
        <li><a href="#install">Installation</a></li>
      </ul>
    </li>
    <li><a href="#start">How to start</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
	<li><a href="#contributors">Contributors</a></li>
  </ol>
</details>


## About
a various numerical methods for solving ode's and machine-learning schemes .

## 💻 Built Using <a name = "tech"></a>
* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
* ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)



## 🏁 Get Started /Installation <a name = "install"></a>
1. **Clone the repository**
```
git clone https://github.com/Ibrahim-Abdelqader/ML-Numerical-Diabetes-Glucose-ODE-Modeling.git
```
2. **Install Visual Studio Code || PyCharm**


3. **Open the folder in IDE**

4. **install dependencies**
```
pip install 
```

5. **Build the project**


6. **You can run through**


## 📝 Numerical Methods <a name = "features"></a>
<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Description</th>
      <th>Book</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ISODA</td>
      <td>A stiff ODE solver using adaptive step-size control and automatic method switching (e.g., BDF and Adams). Often used in real-world stiff ODE systems.</td>
      <td>✅</td>
    </tr>
	     <tr>
      <td>Classical 4th-order Runge-Kutta method</td>
      <td>Widely used, fixed-step solver. Computes intermediate slopes (k1–k4) to estimate the solution with good accuracy.</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Newton-Raphson with Backward Euler</td>
      <td>A first-order implicit method solving nonlinear equations at each step using Newton-Raphson. Very stable for stiff problems but requires Jacobian.</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Trapezoidal</td>
      <td>An implicit method averaging the slope at the current and next time steps. It’s A-stable and more suited for moderately stiff problems.</td>
      <td>❌</td>
    </tr>
 
<tr>
      <td>Midpoint</td>
      <td>A second-order explicit method that estimates midpoint to improve over Euler’s method. More accurate but still not suitable for stiff equations.</td>
      <td>❌</td>
    </tr>
  </tbody>
	
</table>
🧠 Key Notes:

- ISODA Automatically chooses the most efficient and stable solver,
Very robust for chemical kinetics, control systems, and biological models, where stiffness often arises unpredictably.
- RK4 is a good general-purpose method when high accuracy is needed, and stiffness is not a concern.
- Trapezoidal rule is often seen as a balance between accuracy and stability.
- Newton-Raphson is used to solve the nonlinear algebraic equation resulting from implicit methods like Backward Euler.
- Midpoint is a simple second-order method, more accurate than Euler, but less so than RK4.

## 📷 Screenshots <a name = "screenshots" ></a>

<div name="Screenshots" align="center">
   <img width=60% src="Screenshots/Screenshot_1.png" alt="logo">
   <hr>
    <img width=60% src="Screenshots/Screenshot_3.png" alt="logo">
    <hr>
  
   <img width=60% src="Screenshots/Screenshot_2.png" alt="logo">
   <hr>
</div>

## Contributors <a name = "contributors"></a>
<table align="center">
  <tr>
    <td align="center">
    <a href="https://github.com/hamdy-cufe-eng" target="_black">
    <img src="https://avatars.githubusercontent.com/u/183446123?s=96&v=4" width="100px;" alt="Hamdy Ahmed"/>
    <br />
    <sub><b>Hamdy Ahmed</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/Karim-Mohamed-Elsayed" target="_black">
    <img src="https://avatars.githubusercontent.com/u/183163245?v=4" width="100px;" alt="Karim Mohamed"/>
    <br />
    <sub><b>Karim Mohamed</b></sub></a>
    </td>
     <td align="center">
    <a href="https://github.com/David-Amir-18" target="_black">
    <img src="https://avatars.githubusercontent.com/u/183446535?v=4" width="100px;" alt="David Amir"/>
    <br />
    <sub><b>David Amir</b></sub></a>
    </td>
    
  </tr>
 </table>
