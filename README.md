# DC24SEVEN
Udržujte Discord profil napořád ONLINE

1. Zaregistrujte Render – https://render.com/
2. Render -> NEW+ -> Web Service -> build and deploy from a Git repository -> Next
3. Na konci stránky -> Public Git repository -> https://github.com/klauny/DC24SEVEN -> Continue
4. You are deploying a web service for klauny/DC24SEVEN
   - Name: anything you want
   - Runtime: Node
   - Build Command: npm install
   - Start Command: node index.js
   - Instance type: Free
   - Enviroment variables -> NAME_OF_VARIABLES: token -> value: váš DC token
5. Získejte token svého DC účtu:
   - přihlaste se do svého Discordu v prohlížeči a mějte status ONLINE
   - stiskněte: F12 (Google Chrome) -> přejděte na Síť -> klikněte na nějaký dialog/server/kanál na DC
   - najděte "science" -> přejděte na záhlaví -> najděte: "autorizaci" -> zkopírujte tento token (dlouhý text,směs znaků)
6. Create web Service -> počkat až služba dokončí procesy (v logu se zobrazí: Your service is live 🎉)
7. Vlevo nahoře je link: https://anything-you-want.onrender.com
   - po rozkliknutí se zobrazí: I'm alive (pokud ne, restarujte službu manual Deploy -> Restart service)
   - zkopírujte webovou adresu
12. Přejděte na https://cron-job.org, zaregistrujte se.
13. Klikněte na: CREATE CRONJOB
   - Title: anything you wan
   - URL: https://anything-you-want.onrender.com
   - Execution schedule: Every 2 minutes
   - CREATE
14. Hotovo, váš profil je online na pořád.
