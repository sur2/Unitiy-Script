# Unity-Script
Unity Script를 작성합니다.

## LifeCycle

# void Awake()
- 스크립트가 실행 될 때 최초로 1회 호출

# void OnEnable()
- 오브젝트를 활성화 할 때 마다 호출

# void Start()
- Update 함수 호출 전에 1회 호출 되며, Awake 함수가 이전에 호출되어야 호출 할 수 있다.

# void FixedUpdate()
- 유니티 엔진의 물리 연산을 담당하며 기본적으로 0.02초 마다 호출된다.

# void Update()
- 프레임 마다 호출되는 함수로 게임의 핵심 로직에 사용된다. 하드웨어 계산 성능에 영향을 받는다.

# void LateUpdate()
- 모든 Update 로직이 실행 된 후에 호출된다. 주로 카메라 이동 로직에 사용된다.

# OnDisable()
- 오브젝트 또는 스크립트가 비활성 될 시 호출

# OnDestory()
- 오브젝트의 마지막 프레임이 업데이트 된 후 호출되며 데이터 해제를 의미합니다.
