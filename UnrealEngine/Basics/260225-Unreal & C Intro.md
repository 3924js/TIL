 블루프린트의 경우
 * 언리얼
	 * 프로젝트
	 * 레벨
	 * 블루프린트(Blueprint)
		 * 언리얼에서 제공하는 비주얼 스크립팅(Visual scripting) 언어, 노드들의 연결로 구성
	 * 이벤트(Event)
		 * 사건이 발생했을때 호출되는 함수들
		 * BeginPlay: 게임 플레이가 시작될 때 호출되는 함수
		 * Tick: 매 프레임마다 호출되는 함수
	 * 함수(Function)
		 * 연산이나 기능을 가지고 작동하는 노드
		 * Print String: 기본적인 언리얼 출력 함수
	 * 변수(Variable)
		 * 변할 수 있는 값을 저장, 언리얼에서 대게 속성(Property)로 지칭
		 * Boolean
		 * 정수
			 * Byte
			 * Integer
			 * Integer64
		 * Float
		 * Name(불변인 문자열)
		 * String
		 * Text(다국어 변환이 되는 문자열)
	 * 변수를 블루프린트의 EventGraph로 드래그하면 Get혹은 Set을 할 수 있음
		 * Get: 변수 값에 대해 한 접근, Read에 해당
		 * Set: 변수 값을 설정, Write에 해당
   * 연산 노드
     * 비교 연산 노드
       * ==
       * !=
       * <
       * \>
       * <=
       * \>=
     * 논리 연산 노드
       * And
       * Or
       * Not
       * Xor
	 * 흐름 제어
		 * Sequence: 주어진 노드들의 순차적인 실행을 제어
		 * Branch:
		 * 반복문
		 * 열거형
     * 구조체
     * Switch
       * 주어진 값에 따라