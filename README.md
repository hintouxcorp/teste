# 🗺️ Prospector de Geolocalização

Um gerenciador de prospecção com capacidade de registrar clientes no mapa, criar raios de atuação com registros de vendas e relatórios automatizados.

![desenvolvimento](https://img.shields.io/badge/Em%20Desenvolvimento-8A2BE2)
![python](https://img.shields.io/badge/python-3.8.0-blue)
![mit](https://img.shields.io/badge/license-MIT-yellow)

## 📝 Descrição

O prospector de Geocalização ajuda o usuário a registrar suas vendas possibilitando marcação de visitas a clientes ajudando a criar funil de vendas além de ter dashboard interativo
para ajudar na visualização dos dados para melhor insights.


mapa em tempo real dos clientes:

<img src="map.jpg" width="300">

---

## 🛠️ Funcionalidades

- adicionar pin no mapa (cliente)
- preencher formulário no pin
- visualizar pins pelo estado
- salvar pin
- relatório de clientes
- criar produtos
- associar produtos a clientes
- funil de vendas

---

## 🖥️ Tecnologias

- python 3.8.0
- django
- django rest framework
- react
- typescript
- html
- css
- api

---

## ⚙️ Instalação

1. Faça um clone do repositório com:
```bash
git clone git@github.com:hintouxcorp/teste.git
```

2. Logo após clonar o repositório crie um ambiente virtual para instalar as dependências com:
```python
python -m venv venv
```

3. A seguir ative o ambiente virtual caso ainda não o ativou:

**Windows**
```python
venv/Scripts/Activate
```

**Linux**
```python
source venv/bin/Activate
```

4. Após isso instale as dependência com:
```python
pip install -r requirements.txt
```

**Com esses passos você já poderá utiliza-lo**

---

## 📋 Como usar:

1. Inicie o servidor com:
```python
python manage.py runserver
```
2. Navegue nas opção Mapa
3. Marque um local como base
4. Escolha o range da base
5. Escolha um local
6. Preencha o formulário daquele local
7. Crie um produto
8. Associe um produto aquele local
9. Utilize o relatório
10. Navegue até o funil

---

## ⚖️ Licença:
Este projeto está sob a licença MIT