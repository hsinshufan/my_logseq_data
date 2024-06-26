- The Complete 2024 Software Testing Bootcamp(https://www.udemy.com/course/testerbootcamp/)
	- Software Development
		- V-Model
		  collapsed:: true
			- ![image.png](../assets/image_1715146620863_0.png)
		- #Agile
			- 12 principles
			- 4 values
			- Agile & Scrum
				- Agile 是一種精神, 而 Scrum 是一實現 Agile 的一種方法
				- Scrum
					- Divide a project into small iterations --> SPRINTS
						- Each  SPRINT is  from 1 to 4 weeks
					- SPRINT = ITERATION
					- Vision
						- What we are going to develop
					- Doc: product backlog = SRS & BRD
						- user stories : requirements
						- product owner : user stories 的作者
					- ![image.png](../assets/image_1715147304060_0.png)
		- Sequential Development
			- ![image.png](../assets/image_1715147799514_0.png)
		- Agile Software Development
			- ![image.png](../assets/image_1715147870504_0.png)
		- Incremental Development
			- Build one part and deliver build another part and integrate previous parts
			- ![image.png](../assets/image_1715138633972_0.png)
			-
		- Iterative Development
		  collapsed:: true
			- Build a whole application in every iteration (ex. 2 weeks) and improve the application in every iteration
				- minimum number of features and functions that are usable
			- ![image.png](../assets/image_1715138619883_0.png)
		- ![image.png](../assets/image_1715138867066_0.png)
		- Mix use of Incremental & Iterative Development
			- Every Iteration (delivery) is an whole application within every Iteration, apply the Incremental model
			- Ex.
				- 裝潢3個房間 (將同一種類型的工作, 放在一起做 --> Iteration)
					- 先油漆
					- 安裝燈光
					- 擺放家具
				- 裝潢1000個房間
					- 先將第1個房間進行完整的裝潢, 作為 prototype, the get feedback and approval from the client
					- 再對剩餘的999個房間進行 Iteration 裝潢, 先油漆, 安裝燈光, 再擺放家具
			- 同樣的 Task, 少量及大量會採取不同方法進行開發, 所以最好要混合 Incremental & Iterative 開發方式來做
			-
	- Validation & Verification
	  collapsed:: true
		- ![image.png](../assets/image_1715309692813_0.png)
		- ![image.png](../assets/image_1715309743408_0.png)
		- ![image.png](../assets/image_1715309791866_0.png)
	- Objectives of Testing
	  collapsed:: true
		- ![image.png](../assets/image_1715310148716_0.png)
	- Testing & Debugging
	  collapsed:: true
		- ![image.png](../assets/image_1715310490590_0.png)
	- Test process
	  collapsed:: true
		- Plan --> Design --> Execution
			- ![image.png](../assets/image_1715310843676_0.png)
		- Test process Activities
			- Test Monitoring & Control --> Test progress report
			- Test Analysis --> Identify [[Test Scenario]] by assemble sentences
				- Identify what are we going to test
			- ![image.png](../assets/image_1715310890202_0.png)
	- Test Levels
	  collapsed:: true
		- Groups of test activities that are organized and managed together
		- Each test level is an instance of the test process
		- Related to other activities within the software development lifecycle
		- ![image.png](../assets/image_1715311933234_0.png)
		- Unit (Component) Testing --> Developer
			- components are separately testable
		- Integration Testing
			- Interactions between components
			- Component Integration --> Developer
			- System Integration --> Tester
		- System Testing --> Tester
			- ![image.png](../assets/image_1715312302820_0.png){:height 291, :width 689}
		- Acceptance --> User or Stake holder
			- Alpha testing: Test in developer's environment
			- Beta testing: Test in user's environment
	- Testing Types
	  collapsed:: true
		- Functional Testing
		  collapsed:: true
			- Testing what the system does
			- Usually answered with Yes/No
		- Non-functional Testing
		  collapsed:: true
			- Testing how the system performs
			- Hard to answer with Yes/No
			- Usually measured as a range
		- Black -Box Testing
		  collapsed:: true
			- Testing without knowing the internal structure of the system
		- White-Box Testing
		  collapsed:: true
			- Testing while monitoring the internal structure of the system
		- Dynamic Testing
		  collapsed:: true
			- executing the software
		- Static Testing
		  collapsed:: true
			- review requirements, design, user manuals
			- coding review --> white box testing
			- Early testing save time and money
		- Retesting (Confirmation Testing)
			- assure defects are fixed
		- Regression Testing
			- Testing unchanged areas to ensure they are affected by changes
		- Smoke Testing
			- Testing main functionalities to ensure that the build is stable enough to continue testing
			- ![image.png](../assets/image_1715312910420_0.png)
	- [[Test Scenario]]
		- A TEST SCENARIO is defined as any functionality that can test tested
		- Test Condition or Test Possibility
		- Figure out real-world scenarios and use cases from end user's point view
		- Study Requirement documents pertaining to System Under Test (SUT)
			- Business Requirement Specification, BRS
			- Software Requirement Specification, SRS
			- Functional Requirement Specification, FRS
		- Analyze and frame possible system abuse scenarios
		- Enumerate test scenarios that cover every possible feature of the software
		- Create a Traceability Matrix to ensure that every requirement is mapped to a test scenario
		- Facebook Valid Sign Up Test
			- ![image.png](../assets/image_1715334119722_0.png)