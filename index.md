
# Information
- Yasuhira Chiba
- Links  
    [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasuhira-chiba-337094155/)  
    [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YasuChiba)  
    [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@yasuhirachiba)  

# Experiences
- Languages
    - Python, Go, Java, C++, Dart, Swift, JavaScript, TypeScript, etc..
- IoT
    - Raspberry Pi
    - マイコン
        - Arduino
        - ESP-32
            - [BME280_on_ESP-IDF_I2C](https://github.com/YasuChiba/BME280_on_ESP-IDF_I2C)
            - [BME280_Arduino](https://github.com/YasuChiba/BME280_Arduino)
            - [self-balancing-robot](#self-balancing-robot)
- Robotics
    - ROS/ROS2
        - [megarover-ros2](#megarover-ros2)
        - [ros2-android](#ros2-android)
    - Lidar
        - Livox Mid360
            - [megarover-ros2](#megarover-ros2)
        - Livox Horizon
    - Depth Camera
        - Realsense
            - [megarover-ros2](#megarover-ros2)
            - [座標変換方法の記事](https://medium.com/@yasuhirachiba/converting-2d-image-coordinates-to-3d-coordinates-using-ros-intel-realsense-d435-kinect-88621e8e733a)
- Mobile
    - iOS
        - [時間割アプリ](#時間割アプリ)
        - インターンとして[SpeakBuddy](https://www.speakbuddy.com/)の開発
        - Core MLを利用した画像分析アプリ
    - Android
        - [時間割アプリ](#時間割アプリ)
    - Flutter
        - 音響分析アプリ
        - SNS開発
- Web
    - backend
        - Go
            - Cloud FoundryのService Broker実装
                - echo
                - gorm
        - Python
            - IoTアプリケーションのバックエンド
                - Django
                    - django-tenants
            - 機械学習モデルのインターフェース
                - Flask
- AWS
    - AWS上でのウェブ/IoTアプリケーションのアーキテクチャ設計
        - 業務委託にてAWS IoT, ECS, Cognitoなどを組み合わせたアーキテクチャの設計を行いAWS CDKで実装
- SAP BTP
    - SAP CAP, Cloud Foundry, Kyma, SAPUI5, etc..
- Unity
    - [Happiness Finder](https://www.youtube.com/watch?v=ouy7zNP_vwQ)
    - VRシューティングゲーム開発
- Others
    - VPN構築
        - Wireguardで複数企業間での接続テスト環境構築
    - Cloud Foundry
        - Service Broker実装


# Personal/Lab Projects


### Megarover-ros2
自律移動ロボットの実装。車体にメガローバー V3.0を利用し、電源系やLidarとPCの接続基盤などは自前で実装。

- [リポジトリ](https://github.com/YasuChiba/megarover-ros2)

### ROS2-Android
Android端末上でROS2をネイティブ実行させるために、[ros2-java](https://github.com/ros2-java/ros2_java)のビルド周りを整理。
また、その一環でROS2のビルドシステムであるcolconのプラグイン（colcon-ros-gradle）に対してプルリク作成&マージ済み。
- [ビルドツール](https://github.com/YasuChiba/ros2-android-build)
- [サンプルアプリ](https://github.com/YasuChiba/ros2-android-test-app)
- [colcon-ros-gradle](https://github.com/YasuChiba/colcon-ros-gradle)
- [ROS2-On-Androidの解説記事](https://medium.com/@yasuhirachiba/how-to-use-ros2-on-android-natively-43f9e4595621)

### Self-balancing robot  
２輪の自立ロボットを車体から自作。ESP-32にIMU等を接続し、モーター類はAlliexpressで購入。  
- links
    - [リポジトリ](https://github.com/YasuChiba/Self-balancing-robot)
    - [動画](https://photos.app.goo.gl/ZCzcyj6V4Hjbia5AA)

### 時間割アプリ  
ICUの学生向け時間割管理アプリ。  
リリースから４年程は毎年1500人程度のアクティブユーザーが存在。  
初版はAndroid向けに実装。その後iOS向けに実装。  
- links
    - [facebook](https://www.facebook.com/timetableforicu)
    - [記事](http://weeklygiants.co/?p=8872)
