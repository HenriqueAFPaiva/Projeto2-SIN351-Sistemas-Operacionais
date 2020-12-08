# Projeto-SIN351

**Grupo:**
  - José Eduardo - 5964 - T2
  - Henrique Alves - 5968 - T2

  
**Link repositório:** https://github.com/HenriqueAFPaiva/Projeto-SIN351-2

**Objetivo:**
  Desenvolver um algoritmo de subistituição de páginas (Memória Virtual) em linguagem C para a disciplina de **Sistemas Operacionais - SIN351**
  
**Algoritmo de Substituição escolhido:**
  - FIFO;
  
**Erros conhecidos:**
  - Quando o "free(f.itens);" é executado o seguinte erro ocorre: "double free or corruption (out)" e o programa é abortado, por isso o "free(f.itens);" está comentado no código;
  
**Compilar o projeto:**

```gcc -Wall vmm.c```

**Executar:**

```./vmm random 10 < anomaly.dat```

```./vmm fifo 10 < anomaly.dat```
