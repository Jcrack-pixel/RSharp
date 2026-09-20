#RSharp 

RSharp is a high-performance interpreter built in Rust for executing SharpC+ code. Its unique feature is direct cross-language integration: you can embed Python code inside RSharp blocks, and it will run seamlessly. This allows multi-language development within one environment, maintaining each language's syntax naturally.

No installation is required to code in Python (sys) or C (sys), but Python_full (sys) and C_full (sys) require the real Python installed on the machine and the real C. JavaScript and Lua are also available but do not have a full version. Note that C / C_full / Python_full have full access to memory and can execute system commands. Also note that RSharp has full system access, so it is strictly discouraged to run a .shp file whose origin you do not know.
