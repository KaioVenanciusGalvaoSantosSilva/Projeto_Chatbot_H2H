"# Projeto_Chatbot_H2H"
# adicione ao seu site e teste algo como: "oi, esqueci a senha" e veja um exemplo de uma das funcionalidades e poder que a Watson pode prover para seu negócio.

<script>
  window.watsonAssistantChatOptions = {
      integrationID: "284aa4c8-fa72-40dc-9fdf-9cd02114be2a", // The ID of this integration.
      region: "us-south", // The region your integration is hosted in.
      serviceInstanceID: "a8b3db24-85bb-4f75-a8e6-8c977e81fd36", // The ID of your service instance.
      onLoad: function(instance) { instance.render(); }
    };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js"
    document.head.appendChild(t);
  });
</script>
