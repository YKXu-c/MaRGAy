# MaRGAy
Matrix Representation Green function Analysis is a python library based on Python, C++ and Rust created for building calculation framework of condensed matter problem in matrix representation and matrix represented green function.

**Here are the basic Dev Principles of this Package MaRGAy**:
- All data in stream are array with `ndarry==2` in numpy(2 dimensional Matrix);
- ISP and DIP must be obeyed(that means each sublibrary is independent with each other, and interfaces are used to solve the difference of data type of different language);
- Prototype is written by Python, refactoring and upgrade will be done by following rules:
  - algorithem for **ReinforcementLearning** and most **interfaces** should use **Python**;
  - algorithem for **parrallel** or **linear algebra operation** that **need CUDA/BLAS .etc libs** should use **C++**;
  - else optimization should use **Rust**.
 
