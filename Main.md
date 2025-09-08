import View.LoginView;
import javafx.application.Application;
import javafx.scene.Scene;
import javafx.stage.Stage;

public class Main extends Application {

    @Override
    public void start(Stage stage) {
        LoginView loginView = new LoginView(stage);
        Scene scene = new Scene(loginView.getView(), 400, 300);
        stage.setTitle("App de Notas");
        stage.setScene(scene);
        stage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}
