# Instruction for Homework 1

## Installation

- Download the code
  ```shell
  git clone https://github.com/KuangHaofei/ImageBasedModellingEdu.git
  cd ImageBasedModellingEdu
  git checkout hw
  ```

- Install requirements
  ```shell
  sudo apt install libjpeg-dev libtiff-dev
  ```

- Compile the source code
  ```shell
  cd ImageBasedModellingEdu
  mkdir build && cd build
  cmake ..
  make -j 8
  ```
## Task 1-1

- outputs of the code:
  ![task1-1](./imgs/task1-1.png)

## Task 1-2

- outputs of the code:
  ![task1-2](./imgs/task1-2.png)

## Task 1-3

- outputs of the code:
  ![task1-3](./imgs/task1-3.png)

## Task 1-4

- outputs of the code:
  ![task1-4](./imgs/task1-4.png)

## Task 1-5

- outputs of the code:
  ![task1-5](./imgs/task1-5.png)

## Task 1-6

- Results:
  - Nearest Neighbor
    - output:
      ![task1-6_nn](./imgs/task1-6_nn.png)
    
    - matching results:
      ![matching_nn](./imgs/matching_featureset_nn.png)
    
  - Lowe's Ratio
    - output:
      ![task1-6_lowe-ratio](./imgs/task1-6_lowe-ratio.png)
    
    - matching results:
      ![matching_lowe-ratio](./imgs/matching_featureset_lowe-ratio.png)