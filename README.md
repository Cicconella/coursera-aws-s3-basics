# _AWS S3 Basics_

## Criar _Bucket_ no S3

O _Bucket_ é um repositório em que vamos guardar os dados. Ao criar o _Bucket_, definimos o **tipo de acesso** e o **tipo de criptografia**.

A AWS pode fazer a criptografia no lado do _server_ ou do _client_:
Se a criptografia é feita do _server_, temos duas opções:

- **Amazon S3 key (SSE-S3)**: a Amazon cria as chaves de criptografia, SSE-S3: Server side encryption - SE.
- **AWS Key management Service Key**: As chaves são organizadas pela Amazon e pelo criador do _Bucket_.

É possível criar **Bucket policies:**

Definir regras para o upload de arquivos, por exemplo, definir a regra de no receber arquivos descriptografados.

É possível fazer o controle de versões da pasta.

As configurações podem ser alteradas.

## _Upload_ dos dados

É possível criar pastas dentro do Bucket.

Ao dar o upload, podemos escolher a Storage class e a permissão de leitura.

Cada objeto terá uma URL, mas só será possível de ver no _browser_ se tiver com a opção de _public access_ e o _Bucket_ também ser público.

### _Storage class_

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
