### Installazione di Swift su Linux

1. **Apri il terminale** premendo `Ctrl+Alt+T`

2. **Scarica Swift**:
   ```bash
   wget https://download.swift.org/swift-5.9-release/ubuntu2204/swift-5.9-RELEASE/swift-5.9-RELEASE-ubuntu22.04.tar.gz
   ```

3. **Estrai il file**:
   ```bash
   tar xzf swift-5.9-RELEASE-ubuntu22.04.tar.gz
   ```

4. **Aggiungi Swift al PATH**:
   ```bash
   echo 'export PATH=/percorso/alla/cartella/swift-5.9-RELEASE-ubuntu22.04/usr/bin:$PATH' >> ~/.bashrc
   source ~/.bashrc
   ```

5. **Verifica l'installazione**:
   ```bash
   swift --version
   ```
