#### Get to know about your planets. I really enjoy seeing your Fork and contribution :rocket:

*  This is a simple application that explains the planets and gives addtional detailed information about them

![(1)](https://github.com/Joamofa1/PlanetsEducationApp/blob/main/Screens/Screen.png)

![(2)](https://github.com/Joamofa1/PlanetsEducationApp/blob/main/Screens/screen2.png)


## :computer: Portfolio and Resume
* [LinkedIn](https://www.linkedin.com/in/justice-ohene-amofa-349b44173/)
* [Portfolio Website](https://joamofa1.github.io)




# Main.dart File

```import 'package:flutter/material.dart';

import 'home_page.dart';
 

 /* 
  Progrun.ir
  This site is our resume 
  */
 
void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {

    return MaterialApp( 
      theme: ThemeData(
          fontFamily: 'Glory',
          primaryColor: const Color(0xFFFEFCFF), 
          visualDensity: VisualDensity.adaptivePlatformDensity,
          scaffoldBackgroundColor: const Color(0xFFFEFCFF),
          textTheme: Theme.of(context)
              .textTheme
              .apply(bodyColor: Colors.black, displayColor: Colors.black, fontFamily: 'Glory'),
      ),
      debugShowCheckedModeBanner: false,
      home: Directionality(
        textDirection: TextDirection.rtl,
        child: HomePage(),
      ),
    );
  }
} ```
