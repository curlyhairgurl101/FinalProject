#include "std_lib_facilities_4.h"
#include "Simple_window.h"
#include "Graph.h"
#include "GUI.h"

using namespace Graph_lib;

class pancake_window2 : Graph_lib::Window {
public: pancake_window2 ( Point xy, int w, int h, const string& title );
	
	
private:
	//Widgets
	Button quit_button2; //quit button
	In_box initials; //initials in_box
	Button enter_button; //enters initials that's in in_box
	Button dir_button; //next window to play
	//Button score_button; //displays top 5 player's scores
	Button back_button; //back to directions
	
	Button two_button;
	Button three_button;
	Button four_button;
	Button five_button;
	Button six_button;
	Button seven_button;
	Button eight_button;
	Button nine_button;

	void enter();
	void quit2();
	void dir();
	//void score();
	void back();
	
	void two();
	void three();
	void four();
	void five();
	void six();
	void seven();
	void eight();
	void nine();
	
	//callback functions
	static void cb_quit2(Address, Address);
	static void cb_enter(Address, Address);
	static void cb_dir(Address, Address);
	//static void cb_score(Address, Address);
	static void cb_back(Address, Address);
	
	static void cb_two(Address, Address);
	static void cb_three(Address, Address);
	static void cb_four(Address, Address);
	static void cb_five(Address, Address);
	static void cb_six(Address, Address);
	static void cb_seven(Address, Address);
	static void cb_eight(Address, Address);
	static void cb_nine(Address, Address);
};


pancake_window2::pancake_window2(Point xy, int w, int h, const string& title)
    :Window(xy,w,h,title),
	quit_button2(Point(x_max()-70,y_max()-20), 70, 20, "&QUIT", cb_quit2), //quit button
	initials(Point(315,0),70,20,"Initials: "),
	enter_button(Point(415,0),70,20,"ENTER", cb_enter), //enters initials
	dir_button(Point(300,320),105,20,"HOW TO PLAY", cb_dir),//will eventually go to directions screen
	//score_button(Point(315,y_max()-20),70,20, "SCORES", cb_score),
	back_button(Point(0,y_max()-20),70,20, "BACK", cb_back),
	
	two_button(Point(70,290), 70, 20, "&2", cb_two),
	three_button(Point(140,290), 70, 20, "&3", cb_three),
	four_button(Point(210,290), 70, 20, "&4", cb_four),
	five_button(Point(280,290), 70, 20, "&5", cb_five),
	six_button(Point(350,290), 70, 20, "&6", cb_six),
	seven_button(Point(420,290), 70, 20, "&7", cb_seven),
	eight_button(Point(490,290), 70, 20, "&8", cb_eight),
	nine_button(Point(560,290), 70, 20, "&9", cb_nine)
	
{
	Graph_lib::Window::Fl_Window::color(24);// changes window color
	attach(quit_button2);
	attach(initials);
	attach(enter_button);
	attach(dir_button);
	//attach(score_button);
	attach(back_button);

	

	attach(two_button);
	attach(three_button);
	attach(four_button);
	attach(five_button);
	attach(six_button);
	attach(seven_button);
	attach(eight_button);
	attach(nine_button);

}
//------------------------------------------------------------------------------
void pancake_window2::cb_quit2(Address, Address pw)
{
	reference_to<pancake_window2>(pw).quit2();
} 
void pancake_window2::quit2()
{
   hide();        // curious FLTK idiom for delete window
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_enter(Address, Address pw)
{
	reference_to<pancake_window2>(pw).enter();
}
void pancake_window2::enter() 
{
	//string player = initials.get_string();
	//string welc = "Welcome, " + player + "!";
	//Text* t = new Text{Point{230,75}, welc.c_str()};
	//t->set_color(Color::black);
	//t->set_font(Graph_lib::Font::courier_bold);
	//t->set_font_size(30);
	//attach(*t);
	//redraw();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_dir(Address, Address pw)
{
	reference_to<pancake_window2>(pw).dir();
}
void pancake_window2::dir() 
{
	cout << "how to button works";
	bool button_pushed = true;
	hide();
	//directions window info
	gui_main();
}
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_back(Address, Address pw)
{
	reference_to<pancake_window2>(pw).back();
}
void pancake_window2::back() 
{
	bool button_pushed = true;
	hide();
	//FlipFlaps_window window(Point(100,100),700,400,"FlipFlaps!");
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

//void FlipFlaps_window2::cb_score(Address, Address pw)
//{
	//reference_to<FlipFlaps_window2>(pw).score();
//}
//void FlipFlaps_window2::score() 
//	//ifstream inFile;
	//inFile.open("SCORE.txt");
	
	//string name;
	//int score;
	
	//if (inFile.fail()){
	//	cerr << "Error Opening File" << endl;
	//}
	
	//int height = 0;
	//while(inFile >> name >> score){
		//ostringstream words;
		//words << name << ' ' << score;
		//Text* top_scores = new Text{Point{315,100+height}, words.str()};
		//top_scores->set_color(Color::white);
		//top_scores->set_font(Graph_lib::Font::courier_bold); 
		//top_scores->set_font_size(20);
		//attach(*top_scores);
		//redraw();
		//height += 20;
	//}
//}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_two(Address, Address pw)
{
	reference_to<pancake_window2>(pw).two();
}
void pancake_window2::two() 
{
	bool button_pushed = true;
	//int m = 2;
//	string n = "AAA";
	//n= initials.get_string();
	hide();
	//////flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_three(Address, Address pw)
{
	reference_to<pancake_window2>(pw).three();
}
void pancake_window2::three() 
{
bool button_pushed = true;
//	int m = 3;
//	string n = "AAA";
//	n = initials.get_string();
hide();
	//flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_four(Address, Address pw)
{
	reference_to<pancake_window2>(pw).four();
}
void pancake_window2::four() 
{
	bool button_pushed = true;
	//int m = 4;
	//string n = "AAA";
	//n = initials.get_string();
	hide();
	//flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_five(Address, Address pw)
{
	reference_to<pancake_window2>(pw).five();
}
void pancake_window2::five() 
{
	bool button_pushed = true;
//	int m = 5;
	//string n = "AAA";
//	n = initials.get_string();
hide();
	//flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_six(Address, Address pw)
{
	reference_to<pancake_window2>(pw).six();
}
void pancake_window2::six() 
{
	bool button_pushed = true;
	//int m = 6;
	//string n = "AAA";
	//n = initials.get_string();
	hide();
	////flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_seven(Address, Address pw)
{
	reference_to<pancake_window2>(pw).seven();
}
void pancake_window2::seven() 
{
	bool button_pushed = true;
	//int m = 7;
	//string n = "AAA";
	///n = initials.get_string();
	hide();
	//flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_eight(Address, Address pw)
{
	reference_to<pancake_window2>(pw).eight();
}
void pancake_window2::eight() 
{
	bool button_pushed = true;
	//int m = 8;
	///string n = "AAA";
	//n = initials.get_string();
	hide();
	////flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
	gui_main();
}

//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

void pancake_window2::cb_nine(Address, Address pw)
{
	reference_to<pancake_window2>(pw).nine();
}
void pancake_window2::nine() 
{
	bool button_pushed = true;
	//int m = 9;
	//string n = "AAA";
	//n = initials.get_string();
	hide();
	////flapjack_window game(Point(100,100),700,400,"FlipFlaps!", m, n); //creates flapjack window
gui_main();
}

int main()
try {
pancake_window2 win{Point{100,100},600,400,"canvas"};
return gui_main();
}
catch(exception& e) {
cerr << "exception: " << e.what() << '\n';
return 1;
}
catch (...) {
cerr << "Some exception\n";


}
