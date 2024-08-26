caso os import nao esteja salvos no git, eles estao aqui:


app.js
import { NavigationContainer } from "@react-navigation/native";
import { createDrawerNavigator } from "@react-navigation/drawer";
import { createStackNavigator } from "@react-navigation/stack";
import { enableScreens } from 'react-native-screens';

enableScreens();



import TelaJavaScript from "./componentes/TelaJavaScript";
import TelaReact from "./componentes/TelaReact";
import TelaNode from "./componentes/TelaNode"




babel.config.js
plugins: ['react-native-reanimated/plugin'],




aviso:

pegar a pasta componenetes do eliton e os assets para as imagens.
