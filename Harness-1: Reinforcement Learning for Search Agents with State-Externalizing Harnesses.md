https://arxiv.org/abs/2606.02373

"LLM한테 기억까지 시키지 말고, 검색 상태(memory)를 외부 시스템이 관리하게 하자."
현재의 검색 에이전트(Search Agent)는 대화 기록(transcript)이 계속 길어지는 상태에서 학습된다
<img width="890" height="716" alt="image" src="https://github.com/user-attachments/assets/152e50aa-995c-46ee-b82e-719d56abb86c" />

여기서 Harness란 단순히 skill, memory와 같은 마크다운 파일이 아닌
행동 공간(action space) + 관측 렌더러(observation renderer) + 상태 전이(state transition) + 보상(reward) 를 전부통틀어 이르는 것
