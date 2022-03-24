# name of the project --------------------------

## Starting point ---------------------

flutter_taxi_booking_customer_app has Project has "main.dart" as Entry Point.

https://user-images.githubusercontent.com/48312656/115983462-a721b100-a54d-11eb-8487-d122b5e70901.mp4


------------------------To Generate Android release steps -------------------

Generate FAT APK - flutter clean - flutter build apk --release

Generate split APK's - flutter clean - flutter build apk --split-per-abi --release


------------------------ iOS release steps ----------------------------------

Set iOS deployment target

Follow below steps

setup flutter sdk
get packages
open runner.xcworkspace from ids folder
update version code in yaml
Bellow commands will generate the runner.app file

flutter clean
flutter build ios --release
Now open the xcode run/build to check if project has error

Select Product -> Archive
Follow the uploading steps

------------------------ Developed for ---------------------------

ETIT PROJECT.....
SRI LANKA INSTITUTE OF INFORMATION TECHNOLOGY
MSc. in Enterprise Application Development 2021 - 2022

--------------------- BY -----------------------------------------

MS21912498@my.sliit.lk - Sithira Munasinghe
MS21910968@my.sliit.lk - Pasindu Weerakoon
MS21912702@my.sliit.lk - Thushan Ranasighe
MS21912566@my.sliit.lk - Sanura Wijayarathne
