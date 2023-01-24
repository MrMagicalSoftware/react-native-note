# react-native-note


Installare node
installare expo sudo npm i -g expo-cli
installare expo client






Tools utilizzati in react vc code
react native tools
prettier
material icon theme




Andare su preferenze cercare

formatonsave e abilitare il tutto


____________________________________________

Prima applicazione 


>= expo init DoneWithIt

Differenza tra managed workflow e bare worflow

in bare workflow ho puù possibilità per gestire nativamente la mia app.


>npm start ( per lanciare la mia applicazione)



________________________________________________

Per fare debug su firefox -> menu debug sospendi per exception rilevate.
posso inserire dei valori nella watch windows

Per identificare il platform posso usare Platform



__________________________Detect the orientations of the screen _____________________

nel file app.json è presente il campo orientation : lanscape , portrait o default
con default supporto tutti e due.

Usiamo questa libreria esterna che si chiama hooks.

https://github.com/react-native-community/hooks


_________________________Flex box ________________________________


Mi servono per costruire complessi layout
la proprietà flex : 1 
ricopre tutto lo spazio
0.5 metà spazio

posso avere più flex che si contendono lo spazio
per questo avremo che ad esempio

<View>

    <View style={{flex:2}}>

    </View>

    <View style={{flex:1}}>

    </View>

</View>

Significa che la prima view ha il doppio rispetto al primo



______________________Flex direction ________________________


Se voglio allineare gli elementi non per riga ma per colonna avremo che 


<View style={{flex:2,flexDirection :"row"}}>

row-reverse
column-reverse


_______________________justifyContent, alignItems and alignSelf __________________


Devo sempre capire a quale direzione sto facendo riferimento
in questo esempio avremo che :


style="{{
    flexDirection :"row", //horizontal  <----Asse di riferimento
    justitfyContet : "center"
}}"

Se voglio creare dello spazio identico tra gli elementi
potrei utilizzare:
justifyContent : "space-around" oppure space-evently space-between


Ho una seconda proprietà che si chiama alignItems:"" //Asse secondario

alignItems :"baseline"

Ho anche la proprietà alignSelf


___________________________________flexWrap and alignContent ________________



___________________________________________________________________________


Best ui react native



https://builder.nativebase.io/?utm_source=HomePage&utm_medium=header&utm_campaign=NativeBase_3

...........................

https://reactnativeelements.com/
https://callstack.github.io/react-native-paper/1.0/index.html
https://nativebase.io/
https://akveo.github.io/react-native-ui-kitten/
http://rnmk.xinthink.com/
https://avocode.com/nachos-ui/docs/index.html#!/Showcase/Card

https://shoutem.github.io/docs/ui-toolkit/components/cards






_______________________________Export app ______________________

npm run eject per fare l'export




_______________________________-UTILE _______________________________________

https://reactnative.directory/



___________________________________Note___________________________________

Per migliorare la performance su android conviene usare hermes
https://reactnative.dev/docs/hermes


______________________________INTERESSANTE_________________________________

https://callstack.github.io/react-native-paper/bottom-navigation.html












