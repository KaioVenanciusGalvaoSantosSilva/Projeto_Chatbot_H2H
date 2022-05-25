# Projeto_Chatbot_H2H
Passo-a-Passo </br>
1° Copie o código abaixo</br>
2° Cole no código do seu site HTML</br>
3° Teste algo como "oi, esqueci a senha"</br>
# Veja um exemplo de solução de problemas e poder que a Watson pode prover para seu negócio.
----------------------------------------------------------------------------
<script>
  window.watsonAssistantChatOptions = {</br>
      integrationID: "284aa4c8-fa72-40dc-9fdf-9cd02114be2a", // The ID of this integration.</br>
      region: "us-south", // The region your integration is hosted in.</br>
      serviceInstanceID: "a8b3db24-85bb-4f75-a8e6-8c977e81fd36", // The ID of your service instance.</br>
      onLoad: function(instance) { instance.render(); }</br>
    };</br>
  setTimeout(function(){</br>
    const t=document.createElement('script');</br>
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js"</br>
    document.head.appendChild(t);</br>
  });</br>
</script></br>
----------------------------------------------------------------------------
