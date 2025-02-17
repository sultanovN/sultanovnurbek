---
url: '/contact/'
summary: contact
---


{{< rawhtml >}}
<h1 style="text-align: center;">CONTACT</h1>

{{< /rawhtml >}}



{{< rawhtml >}}

<h2><a href="https://www.linkedin.com/in/nurbeksultanov/" target="_blank">Linkedin</a>  https://www.linkedin.com/in/nurbeksultanov/</h2>


<h2><a href="https://github.com/sultanovN" target="_blank">GitHub</a>  https://github.com/sultanovN</h2>


<h2>email: nurbek.sultanov.dev@gmail.com</h2>
<h2 class="email" id="email">  COPY</h2>
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

