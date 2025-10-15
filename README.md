# Docker-image-creator
# Docker-image-creator

## はじめ方（VS Codeで体験する手順）

1. **このリポジトリをクローン**  
   ```
   git clone <このリポジトリのURL>
   cd icon_generator
   ```

2. **VS Codeでフォルダを開く**  
   VS Codeで `icon_generator` フォルダを開きます。

3. **Docker Desktopを起動**  
   Dockerがインストールされていない場合は、[Docker公式サイト](https://www.docker.com/)からインストールしてください。

4. **サービスを起動**  
   ターミナルで以下を実行します。
   ```
   docker compose up
   ```

5. **Webサービスにアクセス**  
   ブラウザで [http://localhost:4567/identicon](http://localhost:4567/identicon) にアクセスします。

6. **名前を入力してアイコン画像を生成**  
   フォームに好きな名前を入力し、「アイコン画像生成」をクリックすると、オリジナルのアイコン画像（SVG）が表示されます。

---

### 補足

- サービスは `boring-avatars-web`（Web UI）、`boring-avatars-services`（API）、`redis`（キャッシュ）が連携して動作します。
- APIを直接使いたい場合は [http://localhost:3000/beam/80/yourname](http://localhost:3000/beam/80/yourname) などにアクセスしてください。

---<!-- filepath: /root/icon_generator/README.md -->
# Docker-image-creator

## はじめ方（VS Codeで体験する手順）

1. **このリポジトリをクローン**  
   ```
   git clone <このリポジトリのURL>
   cd icon_generator
   ```

2. **VS Codeでフォルダを開く**  
   VS Codeで `icon_generator` フォルダを開きます。

3. **Docker Desktopを起動**  
   Dockerがインストールされていない場合は、[Docker公式サイト](https://www.docker.com/)からインストールしてください。

4. **サービスを起動**  
   ターミナルで以下を実行します。
   ```
   docker compose up
   ```

5. **Webサービスにアクセス**  
   ブラウザで [http://localhost:4567/identicon](http://localhost:4567/identicon) にアクセスします。

6. **名前を入力してアイコン画像を生成**  
   フォームに好きな名前を入力し、「アイコン画像生成」をクリックすると、オリジナルのアイコン画像（SVG）が表示されます。

---

### 補足

- サービスは `boring-avatars-web`（Web UI）、`boring-avatars-services`（API）、`redis`（キャッシュ）が連携して動作します。
- APIを直接使いたい場合は [http://localhost:3000/beam/80/yourname](http://localhost:3000/beam/80/yourname) などにアクセスしてください。

---