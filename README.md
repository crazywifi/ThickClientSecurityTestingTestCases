# ThickClientSecurityTestingTestCases
Thick Client Security Testing Test Cases


We can perform DLL hijacking testing to check if the application loads malicious DLLs placed in the working directory instead of legitimate ones. Tools required: Process Monitor (Procmon), Test DLL, Process Explorer.

We can perform local file manipulation testing to verify whether sensitive configuration or data files (e.g., .ini, .xml) can be modified to alter application behavior. Tools required: Notepad++, Hex Editor, Process Monitor.

We can perform registry modification testing to check if application registry keys can be altered to bypass authentication or change functionality. Tools required: Regshot, Process Monitor, Registry Editor.

We can perform insecure storage testing to ensure sensitive data is not stored in plaintext in local databases, config files, or cache. Tools required: SQLite Browser, Notepad++, BinText.

We can perform network traffic interception testing to check if data transmitted between the client and server is encrypted and protected from tampering. Tools required: Burp Suite, Wireshark, Fiddler.

We can perform authentication bypass testing to verify if login or access control can be bypassed through local modifications or parameter tampering. Tools required: Burp Suite, Process Hacker, Procmon.

We can perform business logic manipulation testing to ensure that workflows cannot be altered by modifying local requests before sending to the server. Tools required: Burp Suite, OWASP ZAP.

We can perform API endpoint fuzzing to identify unexpected responses or security issues in client-server communication. Tools required: OWASP ZAP, Postman, Burp Intruder.

We can perform hardcoded credentials discovery testing to detect usernames, passwords, or API keys stored inside binaries. Tools required: Strings (Sysinternals), BinText, Ghidra.

We can perform reverse engineering testing to analyze executable code for vulnerabilities or sensitive information disclosure. Tools required: Ghidra, IDA Free, x64dbg.

We can perform memory analysis testing to check if sensitive data (like passwords) is stored in process memory. Tools required: Process Hacker, WinDbg, Volatility.

We can perform privilege escalation testing to verify whether the thick client executes high-privilege actions without proper permission checks. Tools required: Procmon, Process Explorer, Windows built-in tools.

We can perform session token manipulation testing to see if session IDs or authentication tokens can be altered or reused. Tools required: Burp Suite, Fiddler, Wireshark.

We can perform code injection testing to check if local inputs are executed or processed in an unsafe way by the application. Tools required: Process Hacker, Custom Scripts, Burp Suite.

We can perform patching & binary modification testing to see if changing the executable’s instructions affects functionality or bypasses controls. Tools required: HxD Hex Editor, Ghidra, x64dbg.
