# 📱 Mobile Security Framework (MobSF)

![MobSF Logo](https://github.com/MobSF/Mobile-Security-Framework-MobSF/raw/master/static/logo.png)

**Mobile Security Framework (MobSF)** é uma plataforma automatizada e tudo-em-um para testes de penetração, análise de malware e avaliação de segurança de aplicativos móveis (Android/iOS/Windows). Ele suporta análise estática e dinâmica, além de oferecer integração com pipelines CI/CD por meio de APIs REST.

---

**Autor**: Vitor Cristiano Fellizatti  
**Faculdade**: FATEC Araras  
**Data**: 22/04/2025  
**Versão**: Beta

---

## 👨‍💻 Desenvolvedores

- **Ajin Abraham** – Fundador e mantenedor principal
- **Dominik Schlecht**, **Magaofei**, **Matan Dobrushin**, **Vincent Nadal** – Colaboradores ativos

## 🚀 Funcionalidades

- **Análise Estática**: Avaliação de código-fonte ou binário sem execução.
- **Análise Dinâmica**: Monitoramento de comportamento em tempo de execução.
- **Análise de Malware**: Detecção de comportamentos maliciosos e vulnerabilidades conhecidas.
- **Integração CI/CD**: APIs REST para automação de testes de segurança.
- **Suporte a Múltiplas Plataformas**: Android (APK), iOS (IPA) e Windows (APPX).

## 🛠️ Instalação

### Usando Docker

```bash
docker pull opensecurity/mobile-security-framework-mobsf
docker run -it --rm -p 8000:8000 opensecurity/mobile-security-framework-mobsf
```

Acesse a interface web em: [http://localhost:8000](http://localhost:8000)

### Manual (Linux)

```bash
git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
cd Mobile-Security-Framework-MobSF
./setup.sh
./run.sh
```

### Manual (Windows)

```bash
git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
cd Mobile-Security-Framework-MobSF
setup.bat
run.bat
```

## 📄 Documentação

Para mais detalhes, consulte a [documentação oficial](https://mobsf.github.io/docs/).

## 📜 Licença

Este projeto está licenciado sob a [GPL-3.0 License](https://github.com/MobSF/Mobile-Security-Framework-MobSF/blob/master/LICENSE).
