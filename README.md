package project;

import jess.JessException;
import jess.Rete;

public class Main {
	
	public static Rete engine;

	public static void main(String[] args) {
		
		engine = new Rete();
		try {
			engine.batch("tes.clp");
			
		} catch (JessException e) {
			// TODO Auto-generated catch block
			e.printStackTrace();
		}
		
	}
}
