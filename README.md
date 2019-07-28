# Radial Menu for ios and android

A new Flutter project.
# How to use it


```
import 'package:radialmenu/radial_menu.dart';
```
```
2 -return MaterialApp(
    theme: ThemeData(primarySwatch: Colors.green),
    home: RadialMenu(
      radius: 150,
      itemSize: 80,
      child: Scaffold(
        backgroundColor: Colors.white,
        appBar: AppBar(
          title: Text("Radial Menu"),
        ),
        body: Center(
            child:Container()
        ),
      ),
      onItemTapped: (i) {
        print("Item Tapped $i");
      },
      list: [
        RadialMenuItem(
            title: "Item One", color: Colors.green, icon: Icons.access_alarm),
        RadialMenuItem(
            title: "Item Two", color: Colors.red, icon: Icons.account_box),
        RadialMenuItem(
            title: "Item Three", color: Colors.teal, icon: Icons.add_a_photo),
        RadialMenuItem(
            title: "Item Three", color: Colors.teal, icon: Icons.add_a_photo),
        RadialMenuItem(
            title: "Item Three", color: Colors.teal, icon: Icons.add_a_photo)
      ],
    ),
  );
  ```

