создал репозиторий webpack-2 клонировал себе C:\_GitHub_\Module_WebPack\

содержимое папки C:\_GitHub_\Module_WebPack\webpack_1
    (КРОМЕ: .git; dist; node_modules)       скопировал в C:\_GitHub_\Module_WebPack\webpack-2

в PS C:\_GitHub_\Module_WebPack\webpack-2>
    npm install

создал в папке js:
    app.js:
        console.log('app worked');
        const game = new Game();
        game.start();
        import { Game, GameSavingData, readGameSaving as loadGame, writeGameSaving as saveGame } from './game';
    domain.js:
        class Character {
        }
        export default Character;
    game.js:
        export default class Game {
            start() {
            console.log('game started');
            }
        }  
        export class GameSavingData {
        }  
        export function readGameSaving() {
        }  
        export function writeGameSaving() {
        }
        import Character from './domain';










в "Git Bach Here": 
git add .
git commit -m "first commit webpack"
git push
