# Formacao_Unity_3D_Game_Developer
DIO - Formacao_Unity_3D_Game_Developer

# Teamplates
## versoes antigas
- 3D e 2d -> teamplates mais antigos
- URP = Universal rendering pipeline -> preferível usar. hoje é o que tem mais esforço da unity
- HDRP =  HD rendering pipeline -> pode paresentar incompatibilidades em alguns casos
- a diferença básica entre os 3 anteriores etá na aplicação de shaders
## versao 6
- so tem urp e hdrp

# Projeto 01 Explorando o Editor
- Projeto criado como urp 3D
- com o botão direito do mouse e WASD podemos movimentar na cena. com Q vamos pra baixo e com E para cima
- na aba game vemos como o jogo ficará. podemos definir o tamannho de tela
- colocamos 16:9, mais proximo do que o jogado ve no final 
- podemos criar na aba game nossas resoluções específicas
- Objetos vazios normalmente são usados como separadores, divisores ou pastas
- componentes são funcionalidades encapsuladas nos Objetos
- cada objeto tem, no inspetor, vários componentes, entre eles o Collider (Ex Box Collider no cubo)
- os coliders são simplesmente a colisão
- em edit colider podemos alterar o colisor do cubo. isso é útil para por exemlo criar ua colisão de espinhos ou campo de força
- o componente Collider não precisa ter a forma do objeto necessariamente
- o componente funciona no unity como o node na godot