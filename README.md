# CMSE821
# Numerical Methods for Partial Differential Equations
Welcome to CMSE 821!  This course covers finite difference methods for partial differential equations.  Partial differential equations are a important tool for describing the world around us.   The key idea is that you can describe relations between how change in space relates to change in time.  A course on variational methods for modeling is a great way to learn how such models are built from the ground up.  Such a class will teach you how to use the language of calculus to write down models in a self-consistent way.  These kinds of models are often used to describe fluid flow, heat transfer, solid mechanics, etc.  When coupled together systems of partial differential equations describe “Multiphysics” dynamics.   This could be describing the structural mechanics of an airplane, whose composite material body undergoes stresses and steranes during flight. Another example is describing how blood, which is incompressible, flows through the body as the heart pumps it, including the viscoelastic stretching and compressing of the veins.  Such complex problems involve many different types of PDE’s describing how different aspects of the system one is modeling.  

Most of the time the models we want to solve are beyond analytic techniques.  Hence, this class will focus on using computers to solve these problems.  In particular computers are good at adding, subtracting, multiplying and dividing, not solving models written in the language of calculus.  the subject of finite difference numerical methods is about writing down self consistent stable approximations that take the form of algebraic equations that we solve in lieu of the continuous models.  by leveraging techniques from calculus and beyond we will construct a systematic methodology for creating a hierarchy of improved approximations that will enable us to create robust solutions to a range of partial differential equations.  

The course will start out and cover elliptic boundary value problems, along with iterative solvers, it will then move on and cover parabolic equations end time stepping methods, and finally the course will end with hyperbolic problems.  In covering an introduction to all three types of classical partial differential equations, you will get a survey of foundational material, includes methods to analyze these approximations.  We note that each of these topics could be a course in its own right.  The course will culminate with a final project where students will solve a problem where all three classical PDE's show up as part of the multi-physics model, in keeping with problems one encounters in the real world.  

We note that now days, an important topic is how to blend numerical methods with data driven surrogates in a stable and robust way.  This is often done when trying to create a model that can bridge scales.   Bridging scales is critical topic in across science and engineering.  time permitting we will cover aspects of this topic.

Students are encouraged to take follow on courses such as finite element methods spectrum/pseudospectral methods, and finite volume methods.  These topics when paired with numerical linear algebra open the door to solving a wide variety of partial differential equations.

## Course Location and Time
- Location - Engineering Building Room 2320
- M-W 10:20am to 11:40am 

## Office Houres
- D319 Wells Hall
- M-W 1:00-2:00

## Contact
- Phone - 517-353-3831
- Email - christli@msu.edu
- Note - I do not respond to email outside of business hours.

## Textbooks
Required Textbook
1. Randall J. LeVeque, Finite Difference Methods for Ordinary and Partial Differential Equa-
tions: Steady-State and Time-Dependent Problems, SIAM, 2007.

## Supplementary Texts
1. Ascher, U. and Petzold, L., Computer Methods for ODEs and DAEs
2. Trefethen, L. and Bau, D., Numerical Linear Algebra
3. Trottenberg, U., Oosterlee, C., and Schuller, A., Multigrid
4. Haller, G., Modeling Nonlinear Dynamics from Equations and Data
5. Boscarino, S., Pareschi, L., and Russo, G., Implicit-Explicit Methods for Evolutionary PDEs
6. da Veiga, L.B. and Lipnikov, K. and Manzini, G., The mimetic finite difference method for elliptic problems


## Downloads

- [Syllabus](materials/CMSE_821-Fall_2025.pdf)
- [Homework 1 - Deu Sep 22nd, 2025](materials/elliptic_pde_problem_set.pdf)
- [Suplment 1 - Deu Sep 22nd, 2025](materials/elliptic_fdm_analysis_problems.pdf)
- [Homework 2 - Deu Oct 20nd, 2025](materials/)
- [Suplment 2 - Deu Oct 20nd, 2025](materials/)
