adk-gemini-web
	main-class: com.google.adk.web.AdkWebServer
	working-directory: D:\Workspace\finance-agent
	Env varibles: GOOGLE_API_KEY= {{}}
	
adk-gpt-web
	main-class: com.google.adk.web.AdkWebServer
	working-directory: D:\Workspace\finance-agent
	Env varibles: OPENAI_API_KEY= {{}}
	
	
To run GPT Multi-tool-agent as an application

GPTMultiToolAgent
	main-class: com.finance.advisor.GPTMultiToolAgent
	working-directory: D:\Workspace\finance-agent
	Env varibles: OPENAI_API_KEY= {{}}
	
	
GeminiMultiToolAgent
	main-class: com.finance.advisor.GeminiMultiToolAgent
	working-directory: D:\Workspace\finance-agent
	Env varibles: OPENAI_API_KEY= {{}}
