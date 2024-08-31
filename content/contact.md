---
url: '/contact/'
summary: contact
---


{{< rawhtml >}}
<div style="display: flex; justify-content: center; align-items: center; margin-bottom: 80px;">
	<h1>CONTACT</h1>
</div>
{{< /rawhtml >}}



{{< rawhtml >}}

<h2><a href="https://www.linkedin.com/in/nurbeksultanovlink/" target="_blank">Linkedin</a></h2>


<h2><a href="https://github.com/sultanovN" target="_blank">GitHub</a></h2>


<h2 class="email" id="email">email: nurbek.sultanov.dev@gmail.com</h2>
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

