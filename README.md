# Environment Information

* Developers of Aras Innovator · As a function from the viewpoint of the user side, "Environment Notification" function is implemented.
* A new "Environment Notification" icon has been added to the toolbar at the top of the screen, and by overlaying the mouse cursor, environmental detail information is displayed on the popup.
* It is also possible to display the environment information icon in the background color set in both "Main screen" and "Item detail screen", you can check the environment at a glance. By doing this, you can reduce mistakes in developing or verifying each environment and each logged-in user.


* Aras Innovatorの開発者・ユーザー側の視点に立っての機能として、「環境通知」機能を実装しています。
* 画面上部のツールバーに「環境通知」のアイコンを新規に追加しており、マウスカーソルを重ねることでポップアップに環境詳細情報を表示します。
* また、「メイン画面」や、「アイテムの詳細画面」の両方に環境情報アイコンが設定された背景色で表示することができ、一目で環境を確認することができます。 これにより各環境や、各ログインユーザの開発や検証の際にミスを減らすことができます。

## History

This project and the following release notes have been migrated from the old Aras Projects page.

Release | Notes
--------|--------
[v11SP6](https://github.com/ArasLabs/environment-info/releases/tag/v11SP6) | Support version 11SP6. Instructions are described in the ReadMe.pdf

#### Supported Aras Versions

Project | Aras
--------|------
[v11SP6](https://github.com/ArasLabs/environment-info/releases/tag/v11SP6) | 11.0 SP6

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **EnvironmentInfo** import package

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\EnvironmentInfo\Import\imports.mf` file in the Manifest File field.
6. Select **ExtCommon**, **Environment notification**, **com.aras.innovator.cui_default** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

#### _Optional:_
Japanese language settings may be applied using the contents of the Language directory and the LanguagePackManagementUtility.

## Usage

Review the [ReadMe-Environment Information.pdf](./Documentation/ReadMe-Environment Information.pdf) for information on using the project. {[English translation](./Documentation/ReadMe-Environment Information-English.docx)}

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by NEOSYSTEM Co., Ltd.
