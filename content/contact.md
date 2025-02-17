---
url: '/contact/'
summary: contact
---


{{< rawhtml >}}
<h1 style="text-align: center;">CONTACT</h1>

{{< /rawhtml >}}



{{< rawhtml >}}

<svg fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" viewBox="0 0 24 24" height="12" width="12">
                        <path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6"></path>
                        <path d="M15 3h6v6"></path>
                        <path d="M10 14L21 3"></path>
                    </svg>
<h2><a href="https://www.linkedin.com/in/nurbeksultanov/" target="_blank">Linkedin</a>  https://www.linkedin.com/in/nurbeksultanov/</h2>

<svg fill="none" shape-rendering="geometricPrecision" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" viewBox="0 0 24 24" height="12" width="12">
                        <path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6"></path>
                        <path d="M15 3h6v6"></path>
                        <path d="M10 14L21 3"></path>
                    </svg>
<h2><a href="https://github.com/sultanovN" target="_blank">GitHub</a>  https://github.com/sultanovN</h2>


<h2>email: nurbek.sultanov.dev@gmail.com</h2>
<h2 class="email" id="email">Click to COPY email</h2>
<p class="message" id="message">Email copied!</p>

<script>
    document.getElementById('email').addEventListener('click', function() {
        const email = 'nurbek.sultanov.dev@gmail.com';
        const textarea = document.createElement('textarea');
        textarea.value = email;
        document.body.appendChild(textarea);
        textarea.select();
        document.execCommand('copy');
        document.body.removeChild(textarea);
        
        const message = document.getElementById('message');
        message.style.display = 'block';
        
        setTimeout(() => {
            message.style.display = 'none';
        }, 3000); // Скрыть сообщение через 2 секунды
    });
</script>
{{< /rawhtml >}}

