Simpen data
 - expo file system

 Animasi:
 - react-native-reanimated

React Native merupakan file based framework kayak next js

 Akses file secara dinamis
 - import { useLocalSearchParams } from 'expo-router';
 - const { slug } = useLocalSearchParams();

 Navigasi ke page-page
 - import { Link } from 'expo-router';
 - <Link href="/about">About</Link>

 - Kalo mau navigasi tp make button
 -  <Link href="/other" asChild>
      <Pressable>
        <Text>Home</Text>
      </Pressable>
    </Link>

  - kalo make function navigasinya
  - import { router } from 'expo-router';
  - router.replace('url')

  - add presentation: 'modal',


 untuk ScrollView
  - bounces={false}
  - showsVerticalScrollIndicator={false}


  Steps:
    - eas build:configure
    - eas build
    - eas update:configure
    - eas build -p android --profile development
    - eas build:run -p android
    - adb logcat "*:E"



