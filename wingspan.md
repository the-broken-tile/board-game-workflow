### Wingspan

```mermaid
graph TD;
    A(Use end of round teal powers)-->BB;
    BB{Is Oceania expansion in play?}--no-->B
    BB--yes-->BBB
    BBB(Discard your nectar tokens)-->B
    B(Score end of round goals)-->C;
    C{Is it the end of round 4?}--yes-->D
    C--no-->E
    D(Proceed to end game scoring)
    E(Remove player cubes from your board)-->F
    F(Refresh the bird tray)-->GG
    GG{Are you playing Duet mode?}--no-->G
    GG--yes-->GGG
    GGG{is the score tied?}--no-->GGGG
    GGG--no-->G
    GGGG(Pass the first player token to the player on second place)
    G(Pass the first player token)
    