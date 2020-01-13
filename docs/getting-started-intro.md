---
id: intro
title: Dat이란 무엇인가요??
sidebar_label: Dat을 소개합니다.
---

Dat is a protocol for sharing data between computers.
Dat은 컴퓨터간에 데이터를 공유하기 위한 프로토콜입니다.
By making sure changes in data are transparent, everyone receives only the data they want, and by connecting computers directly (rather than using a cloud server), Dat powers communities building the next-generation Web.
데이터의 변경이 투명하다는 걸 확신하고, 모두가 자신이 원하는 데이터를 받으며, 클라우드 서버를 이용하기위해 컴퓨터를 직접 연결함으로서, Dat은 차세대 웹을 만들어가는 커뮤니티들을 운영하고 있습니다.

## Welcome to Dat
## Dat에 오신 것을 환영합니다.

Ever tried moving large files and folders to other computers?
다른 컴퓨터로 큰 파일이나 폴더를 옮기려고 해본적이 있나요?
Usually this involves one of a few strategies: being in the same location (USB stick), using a cloud service (Dropbox), or using old but reliable technical tools (rsync).
이때 보통 몇가지 방법이 있습니다. USB 메모리를 이용해 공유하거나, 또는 클라우드 서비스(Dropbox)를 활용하거나, 또는 rsync같이 오래되었지만 신뢰할 수 있는 기술을 사용하거나.
None of these easily store, track, and share your data over time.
하지만 이런 방법들은 오랜시간동안 여러분의 데이터를 쉽게 보관하거나, 추척하거나, 공유하기 힘듭니다.
People often are stuck choosing between security, speed, or ease of use.
사람들은 종종 보안, 속도, 사용용이성 사이에서 꼼짝못하곤 합니다.
Dat provides all three by using a state-of-the-art technical foundation and user friendly tools for fast and encrypted file sharing that you control.
Dat는 최신기술을 바탕으로 이 세 가지 항목과 빠르고 암호화된 파일 공유를 위해 여러분이 통제할 수 있는 사용자친화적인 툴을 제공합니다.

Dat is free software built for the public by an open source consortium of contributors.
Dat은 기여자들의 오픈소스 컨소시업을 바탕으로 공공을 위해 개발되고 있는 자유소프트웨어입니다.
Researchers, analysts, libraries, and universities are [already using Dat](https://www.nytimes.com/2017/03/06/science/donald-trump-data-rescue-science.html) to archive and distribute scientific data.
연구자, 분석가, 사서, 대학에서 과학연구데이터를 보관하고 분산시키기 위해 [이미 Dat을 사용하고 있습니다.](https://www.nytimes.com/2017/03/06/science/donald-trump-data-rescue-science.html)

Developers are building applications on Dat for [browsing peer-to-peer websites](https://beakerbrowser.com) and [offline editable maps](https://www.digital-democracy.org/blog/update-from-the-ecuadorian-amazon/).
개발자들은 [P2P웹사이트를 브라우징](https://beakerbrowser.com)하거나, [오프라인기반의 수정가능한 지도](https://www.digital-democracy.org/blog/update-from-the-ecuadorian-amazon/)를 위해 Dat위에서 다양한 어플리케이션을 만들고 있습니다.
Anyone can use Dat to backup files or share cute cat pictures with a friend.
누구든 파일을 백업하고, 친구와 귀여운 고양이 사진을 공유하기 위해 Dat을 사용할 수 있습니다.
Install and get started today by using the desktop application, command line, or JavaScript library.
오늘 JavaScript라이브러리, 커맨드라인툴, 데스크탑 앱을 사용해 바로 설치하고 시작해보세요.

Ready to try it?
[Head over to Installation to get started.](getting-started-installation.md)
준비가 되셨나요?
[설치하고 시작해보세요.](getting-started-installation.md)

## Why Dat?
## 왜 Dat을 써야하나요?

Cloud services, such as Dropbox or GitHub, force users to store data on places outside of their control.
Until now, it has been very difficult to avoid centralized servers without major sacrifices.
Dat's unique distributed network allows users to store data where they want.
By decentralizing storage, Dat also increases speeds by downloading from many sources at the same time.

Having a history of how files have changed is essential for effective collaboration and reproducibility.
Git has been promoted as a solution for history, but becomes slow with large files, and has a high learning curve.
Git is designed for editing source code, while Dat is designed for sharing files.
With a few simple commands, you can version files of any size.
People can quickly get the latest files or download previous versions.

In sum, we've taken the best parts of Git, BitTorrent, and Dropbox to design Dat.
Learn more about how it all works by reading [How Dat Works](https://datprotocol.github.io/how-dat-works) or get more in depth at [datprotocol.com](https://datprotocol.com).

#### Distributed Network

Unlike cloud services like Dropbox or Google Drive, Dat works on a distributed network.
This means Dat transfers files peer-to-peer, without needing centralized servers.
Dat's network makes file transfers faster, encrypted, and auditable.
You can even use Dat on local networks for offline file sharing or local backups.
Dat reduces bandwidth costs on popular files, as downloads are *distributed* across all available computers, rather than centralized from a single host.

#### Data History

Dat makes it easy for you to save old versions of files.
With every file update, Dat automatically tracks your changes.
You can even direct these backups to be stored efficiently on an external hard drive or a cloud server by using [our archiver](usingdat-server.md).

#### Security

Dat transfers files over an encrypted connection using state-of-the-art cryptography.
Only users with your unique *read* key can access your files, allowing them to download, view, and re-share your files.
To update the contents of a Dat, users must have the *write* key.
By verifying hashes during transfer, Dat makes sure no data is altered or corrupted.
As long as the read key isn't shared outside of your team, the content will remain private, while the *discovery* key and IP addresses of peers sharing the Dat can become known.
Read more about [security in Dat.](learn-more-security.md)

Also please note: There has not been an independent security audit for Dat.

## Who we are

Dat is a vibrant global community of people contributing and building software with the Dat protocol.
The community hosts [weekly meetings](https://comm-comm.datproject.org/) to chat about Dat.

The Dat Project is a fiscally supported project of [Code for Science & Society](https://codeforscience.org), a nonprofit supporting open source tools that benefit science and society. 

These documents are collaboratively maintained on Github under [datproject/docs](https://github.com/datproject/docs).
We welcome corrections and requests for clarification.

Enough reading, more doing?
Head over to [Installation](getting-started-installation.md) to get started.
