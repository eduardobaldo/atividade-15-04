### Aluno
``RF01``, ``RF04``, ``RF0``, ``RF06``, ``RF10``  
- idAluno  
- nome  
- cpf  
- email  
- telefone  
- endereco  
- rfid  
- status  

ContratarPlano()  
agendarAula()  
cancelarAgendamento()  
atualizarStatus()  
registrarAcesso()  
receberNotificacao()  

Ativar()  
Desativar()  
AlterarValor()  

### Plano
``RF01``, ``RF02``, ``RF04``  
- idPlano  
- nome  
- tipo  
- valor  
- ativo

registrar()  
confirmar()  
cancelar()  

### Pagamento
``RF03``, ``RF04``, ``RF09``  
- idPagamento  
- data  
- valor  
- formaPagamento  
- status  

registrar()  
autorizar()  
negar()  

### Acesso
``RF05``, ``RF09``  
- idAcesso  
- dataHora  
- autorizado  

disponibilizarHorario()  
reservarVaga()  
liberarVaga()  
registrarPresenca()  

### Aula
``RF06``, ``RF07``, ``RF09``  
- idAula  
- nome  
- horario  
- capacidadeMaxima  

confirmar()  
cancelar()  

### Agendamento
``RF06``, ``RF10``  
- idAgendamento  
- dataReserva  
- status  

registrar()  

### Presenca
``RF07``  
- idPresenca  
- data  
- presente  

registrar()  
atualizarDados()  
anexarArquivo()  

### AvaliacaoFisica
``RF08``, ``RF10``  
- idAvaliacao  
- data  
- peso  
- imc  
- percentualGordura
- observacoes
- anexo

registrar()  
atualizarDados()  
anexarArquivo()  


### Notificacao
``RF10``  
- idNotificacao  
- tipo  
- dataEnvio  
- status  
- mensagem  

enviar()  
marcarComoLida()  

### Instrutor
``RF07``, ``RF08``  
- idInstrutor  
- nome  
- especialidade  

registrarPresenca()  
realizarAvaliacaoFisica()  

### Recepcionista
``RF01``, ``RF03``  
- idRecepcionista  
- nome  

cadastrarAluno()  
registrarPagamento()  

### Gerente
``RF02``, ``RF09``  
- idGerente  
- nome

gerenciarPlanos()  
emitirRelatorios()
