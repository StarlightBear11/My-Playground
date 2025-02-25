### Installazione di Swift 6.0.3 su Linux

1. **Apri il terminale** premendo `Ctrl+Alt+T`

2. **Scarica Swift 6.0.3**:
   ```bash
   wget https://download.swift.org/swift-6.0.3-release/ubuntu2204/swift-6.0.3-RELEASE/swift-6.0.3-RELEASE-ubuntu22.04.tar.gz
   ```

3. **Estrai il file**:
   ```bash
   tar xzf swift-6.0.3-RELEASE-ubuntu22.04.tar.gz
   ```

4. **Aggiungi Swift al PATH**:
   ```bash
   echo 'export PATH=/percorso/alla/cartella/swift-6.0.3-RELEASE-ubuntu22.04/usr/bin:$PATH' >> ~/.bashrc
   source ~/.bashrc
   ```

5. **Verifica l'installazione**:
   ```bash
   swift --version
   ```
