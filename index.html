<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terminal CV - Network Security Architect</title>
    <style>
        :root {
            --bg: #1E1E1E;
            --text: #E0E0E0;
            --primary: #4CAF50;
            --secondary: #2196F3;
            --accent: #FF5722;
            --prompt: #FFC107;
        }
        
        body {
            font-family: 'Courier New', monospace;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 20px;
            line-height: 1.5;
        }
        
        .terminal {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .terminal-header {
            color: var(--primary);
            margin-bottom: 20px;
            font-size: 14px;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }
        
        .terminal-body {
            margin-bottom: 20px;
        }
        
        .command-line {
            display: flex;
            margin-bottom: 10px;
        }
        
        .prompt {
            color: var(--prompt);
            margin-right: 10px;
            white-space: nowrap;
        }
        
        .input-line {
            flex-grow: 1;
            background: transparent;
            border: none;
            color: var(--text);
            font-family: 'Courier New', monospace;
            outline: none;
            caret-color: var(--primary);
        }
        
        .output {
            margin-bottom: 15px;
            white-space: pre-wrap;
        }
        
        .cmd {
            color: var(--secondary);
            font-weight: bold;
        }
        
        .comment {
            color: #757575;
            font-style: italic;
        }
        
        .success {
            color: var(--primary);
        }
        
        .error {
            color: var(--accent);
        }
        
        .hidden {
            display: none;
        }
        
        /* Efecto cursor parpadeante */
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        
        .cursor {
            display: inline-block;
            width: 10px;
            height: 20px;
            background-color: var(--primary);
            vertical-align: middle;
            margin-left: 2px;
            animation: blink 1s infinite;
        }
    </style>
</head>
<body>
    <div class="terminal">
        <div class="terminal-header">
            === Terminal CV v1.0.0 ===<br>
            Type "help" for available commands
        </div>
        
        <div class="terminal-body" id="terminal-output">
            <div class="output">
<span class="success">user@cv-terminal:~$</span> welcome
<span class="output">
██╗    ██╗███████╗██╗     ██████╗ ███╗   ███╗███████╗
██║    ██║██╔════╝██║     ██╔══██╗████╗ ████║██╔════╝
██║ █╗ ██║█████╗  ██║     ██████╔╝██╔████╔██║█████╗  
██║███╗██║██╔══╝  ██║     ██╔═══╝ ██║╚██╔╝██║██╔══╝  
╚███╔███╔╝███████╗███████╗██║     ██║ ╚═╝ ██║███████╗
 ╚══╝╚══╝ ╚══════╝╚══════╝╚═╝     ╚═╝     ╚═╝╚══════╝
                                                      
Network Security Architect Terminal CV
Type "help" to begin</span>
            </div>
        </div>
        
        <div class="command-line">
            <span class="prompt">user@cv-terminal:~$</span>
            <input type="text" class="input-line" id="command-input" autofocus>
            <span class="cursor"></span>
        </div>
    </div>

    <script>
        // Comandos disponibles
        const commands = {
            help: {
                desc: "Show available commands",
                execute: () => {
                    let output = <span class="cmd">Available commands:</span>\n;
                    Object.keys(commands).forEach(cmd => {
                        output += <span class="cmd">${cmd}</span> - ${commands[cmd].desc}\n;
                    });
                    return output;
                }
            },
            about: {
                desc: "Show professional summary",
                execute: () => {
                    return `<span class="cmd">ABOUT</span>
Network Security Architect with 8+ years experience.
Specialized in:
- SD-WAN architectures
- Zero Trust security
- Cloud networking (AWS/Azure)
- Network automation

Certifications: CCNP, NSE4, AWS Advanced Networking`;
                }
            },
            experience: {
                desc: "Show work experience",
                execute: () => {
                    return `<span class="cmd">EXPERIENCE</span>
<strong>Senior Network Architect</strong> (2021-Present)
- Designed SD-WAN for 80+ global locations
- Reduced costs 40% via MPLS migration
- Implemented Zero Trust policies

<strong>Network Engineer</strong> (2018-2021)
- Configured Cisco ASR routers for BGP
- Automated tasks with Python/Ansible`;
                }
            },
            skills: {
                desc: "List technical skills",
                execute: () => {
                    return `<span class="cmd">SKILLS</span>
<strong>Networking:</strong> Cisco, Juniper, BGP/OSPF, MPLS, SD-WAN
<strong>Security:</strong> FortiGate, Palo Alto, VPN/IPSec, Zero Trust
<strong>Cloud:</strong> AWS VPC, Azure Networking, Hybrid Cloud
<strong>Automation:</strong> Python, Ansible, Terraform`;
                }
            },
            contact: {
                desc: "Show contact information",
                execute: () => {
                    return `<span class="cmd">CONTACT</span>
Email: your.email@example.com
Phone: +56 9 1234 5678
LinkedIn: linkedin.com/in/yourprofile
GitHub: github.com/yourusername`;
                }
            },
            clear: {
                desc: "Clear terminal screen",
                execute: () => {
                    document.getElementById('terminal-output').innerHTML = '';
                    return '';
                }
            },
            sudo: {
                desc: "Admin privileges (just for fun)",
                execute: () => {
                    return <span class="error">user@cv-terminal:~$: Permission denied</span>;
                }
            }
        };

        // Manejar entrada de comandos
        const commandInput = document.getElementById('command-input');
        
        commandInput.addEventListener('keydown', function(e) {
            if (e.key === 'Enter') {
                const command = this.value.trim().toLowerCase();
                this.value = '';
                
                // Mostrar comando ejecutado
                const outputDiv = document.getElementById('terminal-output');
                outputDiv.innerHTML += <div class="output"><span class="success">user@cv-terminal:~$</span> ${command}</div>;
                
                // Procesar comando
                let result;
                if (commands[command]) {
                    result = commands[command].execute();
                } else if (command) {
                    result = <span class="error">Command not found: ${command}</span>\nType "help" for available commands;
                }
                
                if (result) {
                    outputDiv.innerHTML += <div class="output">${result}</div>;
                }
                
                // Scroll automático
                outputDiv.scrollTop = outputDiv.scrollHeight;
            }
        });

        // Efecto de máquina de escribir inicial
        const welcomeText = welcome;
        let i = 0;
        const typingEffect = setInterval(() => {
            commandInput.value = welcomeText.substring(0, i);
            i++;
            if (i > welcomeText.length) {
                clearInterval(typingEffect);
                commandInput.value = '';
                const event = new KeyboardEvent('keydown', {'key': 'Enter'});
                commandInput.dispatchEvent(event);
            }
        }, 100);
    </script>
</body>
</html>
