# thinkphp6 常用的一些扩展类库

>* 修改背景:将TP的项目移植到Laravel
>* 遇到问题:tp和Laravel的全局函数冲突，导致无法调用。
>* 修改方案：重命名tp相关的ORM函数名称，不改变其内容。
>
* 本项目代码代码来着ThinkPHP
* https://github.com/top-think/think-helper

基于PHP7.1+

[![PHP Composer](https://github.com/larvatecn/think-helper/actions/workflows/php.yml/badge.svg)](https://github.com/larvatecn/think-helper/actions/workflows/php.yml)

> 以下类库都在`\\think\\helper`命名空间下

## Str

> 字符串操作

```
// 检查字符串中是否包含某些字符串
Str::contains($haystack, $needles)

// 检查字符串是否以某些字符串结尾
Str::endsWith($haystack, $needles)

// 获取指定长度的随机字母数字组合的字符串
Str::random($length = 16)

// 字符串转小写
Str::lower($value)

// 字符串转大写
Str::upper($value)

// 获取字符串的长度
Str::length($value)

// 截取字符串
Str::substr($string, $start, $length = null)

```