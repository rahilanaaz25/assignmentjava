public class Assignment2 {
	public static void main(String[] ars) {
		float a=heightConvertor(5,0);
		System.out.println("height in cm "+a);
		float b=weightConvertor(101);
		System.out.println("weight in pounds "+b);
		
		
	}
	static float heightConvertor(float heightFeetPart, float heightInchPart) {
		
		return heightFeetPart*=30.48;
		
		}

    static float weightConvertor(int weight) {
		return weight*=2.20462;
		
	}

}
