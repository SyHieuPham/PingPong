<h1>
  IST Assessment
</h1>

<p>Creater: Sy Hieu Pham</p>


<h1>1. Menu</h1>
<h2>This code is present for menu</h2>
<section>
<p>2.	def main_menu():<br>
3.	    global MainMenu<br>
4.	<br>
5.	    MainMenu = tk.Tk()<br>
6.	    MainMenu.title("PING PONG")<br>
7.	    MainMenu.geometry("500x500")<br>
8.	    MainMenu.resizable(0, 0)<br>
9.	<br>
10.	    global Fr1
11.	    Fr1 = tk.Frame(MainMenu, width= 500, height= 500)
12.	    Fr1.pack()
13.	    Fr1.pack_propagate(0)<br>
14.	<br>
15.	    Title = tk.Label(Fr1, text= "Ping Pong!", font= ("ROBOTO", 32))
16.	    Title.pack()<br>
17.	<br>
18.	    Start = tk.Button(Fr1, text= "Start", font= ("ROBOTO", 16), background = "blue", fg= "White", command= lambda: GamePlay())<br>
19.	    Start.pack()<br>
20.	    Start.place(relx= 0.39, rely= 0.4, width= 120)<br>
21.	<br>
22.	    Quit = tk.Button(Fr1, text= "Quit", font= ("ROBOTO", 16), background = "blue", fg= "White", command= lambda: exit(-1))<br>
23.	    Quit.pack()
24.	    Quit.place(relx= 0.39, rely= 0.5, width= 120)<br>
25.	<br>
26.	    MainMenu.mainloop()<br>
</p>
</section>

<style>
  section{
    background: grey;
    color: white;
  }
</style>
