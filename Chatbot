import java.util.Scanner;

public class Chatbot {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Chatbot: Hi! I'm your Java Chatbot. How can I help you today?");

        while (true) {
            System.out.print("You: ");
            String userInput = scanner.nextLine().toLowerCase();

            if (userInput.contains("hello") || userInput.contains("hi")) {
                System.out.println("Chatbot: Hello there!");
            } else if (userInput.contains("how are you")) {
                System.out.println("Chatbot: I'm just a bot, but I'm doing great! How about you?");
            } else if (userInput.contains("bye") || userInput.contains("exit")) {
                System.out.println("Chatbot: Goodbye! Have a great day!");
                break;
            } else if (userInput.contains("name")) {
                System.out.println("Chatbot: I'm just a simple Java chatbot. You can call me JavaBot!");
            } else if (userInput.contains("help")) {
                System.out.println("Chatbot: I can help you with basic questions. Just ask me anything!");
            } else {
                System.out.println("Chatbot: I'm sorry, I don't understand that. Can you rephrase?");
            }
        }
    }
}
