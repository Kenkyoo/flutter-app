# flutter_application_1

App en Flutter que genera combinaciones aleatorias de dos palabras. Se pueden marcar como favoritas, ver el historial de las generadas y borrar las que ya no te gusten.

Es mi primer proyecto con Flutter. Lo armé siguiendo el [codelab oficial](https://docs.flutter.dev/get-started/codelab) y después le mejoré el diseño visual.

## Funciones

- Generar pares de palabras aleatorios
- Marcar y desmarcar favoritos
- Historial con animación de las palabras anteriores
- Lista de favoritos, con opción de eliminar
- Diseño adaptable: barra inferior en pantallas angostas y menú lateral en pantallas anchas

## Tecnologías

- [Flutter](https://flutter.dev/) con Material 3
- [provider](https://pub.dev/packages/provider) para manejar el estado
- [english_words](https://pub.dev/packages/english_words) para generar las palabras

## Cómo ejecutarlo

Necesitás tener [Flutter instalado](https://docs.flutter.dev/get-started/install).

```bash
git clone https://github.com/Kenkyoo/flutter-app.git
cd flutter-app
flutter pub get
flutter run
```

## Qué aprendí

- Estructura básica de una app Flutter (widgets, `StatelessWidget` y `StatefulWidget`)
- Manejo de estado con `provider` y `ChangeNotifier`
- Layouts responsivos con `LayoutBuilder`
- Animaciones simples (`AnimatedList`, `AnimatedSize`, `AnimatedSwitcher`)
- Personalización visual con temas de Material 3

## Créditos

La base de la app viene del codelab [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab) de Flutter.
