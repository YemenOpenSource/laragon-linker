# Laragon linker

## Introduction

The package that will help you use your projects with laragon without the need to put them on www of the laragon path.

## Installation

```sh
composer global require yemenopensource/laragon-linker
```

## Usage

![طريقة استخدام مكتبة laragon linker](docs/assets/طريقة استخدام مكتبة laragon linker.mp4)

Link current directory with laragon/www.

```sh
linker link 
```

Remove current directory from laragon/www.

```sh
linker unlink
```

Get current path of laragon.

```sh
linker path
```

Get paths of linked projects (comming soon).

```sh
linker links
```

