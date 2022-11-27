# WhatsApp 2.0 App UI (Front-end-UI Only)
A clone of the popular Realtime Chat mobile applications WhatsApp in React Native with WhatsApp UI frontend design. The UI contains a WhatsApp-alike main chat screen. Clicking on these `Chats` will be redirected to open a private chat room to allow the user to send messages to make conversations with other users. It contains a list of messages with styles and `Contacts` with different users' statuses.
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***

⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, including unauthorized modifications, forks, pull requests, and other commercial-related uses will be subjected to copyright violation with sebsequent legal concerns.***

## WhatsApp 2.0 App Front-End-UI Overview:
<p align ="center">
  <img src ="https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/WhatsApp%202.0%20App%20UI%20Overview-1.png" width="380" height="848.818181">&nbsp; 
  <img src = "https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/WhatsApp%202.0%20App%20UI%20Overview-2.png" width="380" height="848.818181">
  <img src = "https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/WhatsApp%202.0%20App%20UI%20Overview-3.png"  width="380" height="848.818181">&nbsp; 
  <img src ="https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/WhatsApp%202.0%20App%20UI%20Overview-4.png"  width="380" height="848.818181">
</p> 


# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#method-to-run--test-the-project-locally)<br/> 
[Prerequisites & Setups](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#prerequisites--setups)<br/> 
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md#testing-result)<br/> 
[Tags and Topics]()<br/> 
# Contribution
[Author]()
# Compatibility
|   OS             | Supported          |
| -------          | ------------------ |
| iOS 10+          | :white_check_mark: |
| < iOS 10         | :x:                |
| Android          | ✅                 |
| Expo Web Server  | :x:                |
# Method to Run & Test the Project Locally
### Download the entire project to localhost. 
### Download needed dependencies and extension tools refer to [README](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/README.md)
### Open the project with Vscode, run to test WhatsApp 2.0 UI with `npm start`
### Have Xcode Simulator installed, press `i` to run Metro iOS bundle.
# 🛠️ Developing Languages, Tools, and Techniques Needed
[Expo](https://docs.expo.dev/get-started/create-a-new-app/)<br/> 
[Xcode iOS 16.1 iPhone 14 Simulator](https://developer.apple.com/xcode/)<br/> 
[Vscode](https://code.visualstudio.com/updates/v1_73)<br/> 
[React-Native v0.70.5](https://reactnative.dev/)<br/> 
[Day.js 2kB](https://day.js.org/)<br/> 
[Ether Creative Shadow Generator](https://ethercreative.github.io/react-native-shadow-generator/)<br/>
[Expo Icons](https://icons.expo.fyi)<br/>
[JavaScript](https://www.javascript.com)<br/>
<div>
  <img src= "https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/assets/expo%20icon.png" width = "60" height ="60" title = "EXPO"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-original.svg" width = "60" height ="60" title = "XCODE"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" width = "60" height ="60" title = "VSCODE"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" width = "60" height ="60" title = "REACT"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg"  width = "60" height ="60" title = "javascript"/>&nbsp; 
</div>

# Prerequisites & Setups
In local Console, initialize to create the react expo app running:
```bash
npx create-expo-app WhatsApp2.0
```
Configure the Xcode iOS Simulator:<br/> 
https://developer.apple.com/forums/thread/678469<br/> 
Xcode -> Preferences -> locations -> "Command Line Tools"<br/> 
Open the created project in Vscode and start the server development at Terminal:
```bash
npm start
```
Press i to open iOS Simulator.<br/> 
Successfully started Expo Developer Tool Metro Bundler with IOS Simulator.<br/> 
[started expo with ios simulator.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/started%20expo%20with%20ios%20simulator.png)<br/>
# Synchronous Developing Notes
## ***Build the chat list item:***
Insert sample chat container, chat content and customize styles in [/ChatListItem/index.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/components/ChatListItem/index.js):
```JavaScript
  <View style={styles.content}>
                <View style={styles.row}>
                    <Text style={styles.name}>Scarlett</Text>
                    <Text style={styles.subTitle}>8:30</Text>
...
 const styles = StyleSheet.create({
    container: {
        flexDirection: 'row',
        marginHorizontal: 10,
        marginVertical: 5,
        height: 70,
...
```
[chat list items created.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/chat%20list%20items%20created.png)<br/>
Add props:
```JavaScript 
const ChatListItem = (props) => {
    console.log(props);
```
[fetched props in log.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/fetched%20props%20in%20log.png)<br/>
Import chat list of profile pictures into [ChatsScreen.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/src/screens/ChatsScreen.js):
```JavaScript 
import { View, Text, FlatList } from 'react-native'; import chats from '../../assets/data/chats.json'; import ChatListItem from '../components/ChatListItem'; const ChatsScreen = () => {
    return (<FlatList data={chats} renderItem={({ item }) =>
<ChatListItem chat={item} />} />
); };
export default ChatsScreen;
```
[list of chatters profiles showed up.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/list%20of%20chatters%20profiles%20showed%20up.png)<br/>
Remove `align-item: center` in [App.js](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/App.js)






# Debugging&Troubleshooting
Image Error: `Image source = {{uri:’...’}}` not displaying image on iOS Bundle. DEBUGGING: https://github... URL prefix blocked, click Download in github image to obtain a different downloading url. Use CMD+D to inspect elements. SHIFT+ i to switch iOS simulators.
# Testing Result
[started expo with ios simulator.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/started%20expo%20with%20ios%20simulator.png)<br/>
[chat list items created.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/chat%20list%20items%20created.png)<br/>
[fetched props in log.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/fetched%20props%20in%20log.png)<br/>
[list of chatters profiles showed up.PNG](https://github.com/KrystalZhang612/WhatsApp-2.0-App-UI/blob/main/list%20of%20chatters%20profiles%20showed%20up.png)<br/>



















