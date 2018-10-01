Problem: Q-Learning 을 신경망으로 구현하면 학습이 상당히 불안정해진다.

Deep Mind's Solution

1. 과거의 상태를 기억한 뒤 그중에서 임의의 상태를 뽑아 학습시키는 방법을 사용.

   효과: 특수한 상황에 치우치지 않도록 학습시킬 수 있어서 더 좋은 결과를 내는대 도움이 됨.

   Reply memmory

2. 손실값 계산을 위해 학습을 진행하면서 최적의 행동을 얻어내는 기본 신경망과 얻어낸 값이 좋은 선택인지 비교하는 목표 신경망을 분리하는 방법을 사용한다. 그리고 목표 신경망은 계속 갱신하는 것이 아니라,기본 신경망의 학습된 결과값을 일정 주기마다 목표 신경망에 갱신해줌.

   => 안정된 학습을 위해, 학습을 진행하면서 최적의 행동을 얻어내는 기본 신경망과 얻어낸 값이 좋은 선택인지 비교하는 목표신경망이 분리 되어 있습니다. 



DQN, Charateristic

에이전트에서 DQN에 상태를 넘겨줄 때는 한 프레임의 상태만 넘겨준다. 다만 DQN이 상태를 받으면 해상 당태만이 아니라 STATE_LEN -1 개의 앞 상태까지 고려해서 현재의 상태로 만들어 저장한다.

즉 상태 0은, t-3, t-2, t-1, t의 프레임을 고려한 상태를 담고있다. 프레임의 갯수는 4개인것이다.

# Reinforcement Learning Architectrue

- Agent
  - Artificial Neural Network that will used by agent.
- Environment
