# [2024년 1학기] 확률 최적 제어

- 강의자 : 서울시립대학교 전자전기컴퓨터공학부 박경훈 교수(gyunghoon.park@uos.ac.kr)
- 강의 학기 : 2024년 1학기

본 repo는 2024년 1학기 개설된 *제어시스템특론* 교과목의 강의 설명 및 MATLAB/Simulink 기반 예제들을 공유하기 위해 작성되었습니다.

**(강의가 종료되는 2024년 1학기 말까지 수시로 업데이트될 예정입니다.)**

### 강의 구성 및 교안

본 교과목은 크게 2가지 파트로 나누어 구성되어 있습니다. 
- **Probability Systems Analysis (PSA)** : 확률 및 랜덤 프로세스에 대한 기초적인 내용을 복습합니다.
  - (2024년 1학기 기준) PSA 파트는 Stanford University의 [Sp22-EE-178-01](https://canvas.stanford.edu/courses/155726) (Instructor : Prof. Abbas El Gamal) 강의 교안 및 내용을 따라갑니다.
- **Stochastic Control (SC)** : 본 교과목의 주요 내용으로, 확률 기반 최적 제어 기법의 전반적인 내용을 학습합니다.
  - (2024년 1학기 기준) SC 파트는 Stanford University의 [EE365](https://web.stanford.edu/class/ee365/index.html) (Instructor : Sanjay Lall) 강의 교안 및 내용을 따라갑니다.

### MATLAB/Simulink 모의실험 예제

본 교과목의 수업 내용의 이해를 돕기 위하여, 아래의 MATLAB/Simulink 파일을 제작하였습니다. 

- **PSA**
- **SC**
  - (02) Shortest path
  - (03) Probability and Monte Carlo
    - Monte Carlo 시뮬레이션 : [mlx](/SC/monte_carlo_example.mlx) / [pdf](/SC/monte_carlo_example.pdf)
  - (04) Markov chains
    - Inventory model 시뮬레이션 : [mlx](/SC/inventory_model_example.mlx) / [pdf](/SC/inventory_model_example.pdf)

**주의 사항**
- 위 예제들은 `MATLAB Statistics and Machine Learning Toolbox` 함수를 활용합니다. 
- 위 예제들은 `MATLAB 2023b`에서 작성되었습니다.  