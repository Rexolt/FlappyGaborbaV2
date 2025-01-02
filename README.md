 Flappy Gaborba - README

# Flappy Gaborba

A Flappy Gáborbá Electron keretrendszerrel.

## Forrásból való buildelés

### Előkövetelmények

*   **Node.js** (ajánlott verzió: 16 vagy újabb)
*   **npm** (Node Package Manager)

### Lépések

1.  **Projekt klónozása**
    
    Nyisd meg a terminált, és futtasd a következő parancsot:
    
    git clone https://github.com/Rexolt/FlappyGaborbaV2.git
    cd FlappyGaborbaV2
                
    
2.  **Függőségek telepítése**
    
    Telepítsd a projekt függőségeit az `npm install` paranccsal:
    
    npm install
                
    
3.  **Fejlesztői mód futtatása**
    
    Indítsd el a projektet fejlesztői környezetben:
    
    npm start
                
    
4.  **Buildelés**
    
    Ha le szeretnéd fordítani a projektet futtatható formátumra:
    
    *   **Windows:**
        
        npm run dist
                            
        
    *   **Linux:**
        
        npm run dist -- --linux
                            
        
    
    A build fájlokat a `dist` mappában találod.
    

### Megjegyzés

Ha hibát tapasztalsz, győződj meg róla, hogy minden előfeltétel teljesült, és a `node_modules` mappa naprakész.

## Kapcsolat

Ha problémád van a projekttel kapcsolatban, jelezd