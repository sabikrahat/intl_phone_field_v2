# International Phone Field Package

> **Note**
>
> `intl_phone_field_v2` is an extension of [intl_phone_field](https://pub.dartlang.org/packages/intl_phone_field). This package has solved all the version related issues and added some new features. The original package is no longer maintained, so we have created this fork to continue its development. For more details about extra features to this package. Please check the [CHANGELOG](CHANGELOG.md) for more details.

A customised Flutter TextFormField to input international phone number along with country code.

This widget can be used to make customised text field to take phone number input for any country along with an option to choose country code from a dropdown. You can also get the currency name and symbol for the selected country.

<!-- ## ⚠️ The package is deprecated and this repository is no longer maintained ⚠️

As of June 2021, I, @marcaureln, have been maintaining this Flutter package initially created by @vanshg395. Regrettably, Vansh has been unresponsive, and I am unable to release new versions (the last release is 6 months old as of writing).

Considering this, I recommend users to explore alternatives on [pub.dev](https://pub.dev/) or, if interested, fork this repository for continued support. Life can be hectic, and I wish Vansh is doing well.

Thank you for your understanding and continued support. -->

<!-- <details>
  <summary>Old Readme</summary> -->

## Screenshots

<img src="https://github.com/sabikrahat/intl_phone_field_v2/blob/main/1.png?raw=true" height="500px"> <img src="https://github.com/sabikrahat/intl_phone_field_v2/blob/main/2.png?raw=true" height="500px"> <img src="https://github.com/sabikrahat/intl_phone_field_v2/blob/main/3.png?raw=true" height="500px">

## Installing

To use this package:

Run this command:

```yaml
dart pub add intl_phone_field_v2
```

Or, add the following to your `pubspec.yaml` file:

```yaml
dependencies:
  intl_phone_field_v2: ^<latest_version>
```

Sometimes you may want to use the latest version of the package, instead of a published version. To do that, use the `git` syntax:

```yaml
dependencies:
  intl_phone_field_v2:
    git:
      url: git://github.com/sabikrahat/intl_phone_field_v2.git
      ref: main
```

## How to Use

Simply create a `IntlPhoneField` widget, and pass the required params:

```dart
IntlPhoneField(
    decoration: InputDecoration(
        labelText: 'Phone Number',
        border: OutlineInputBorder(
            borderSide: BorderSide(),
        ),
    ),
    initialCountryCode: 'IN',
    onChanged: (phone) {
        print(phone.completeNumber);
    },
)
```

Use `initialCountryCode` to set an initial Country Code.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

Comment on Issue or Pull Request, asking @all-contributors to add a contributor:

```shell
@all-contributors please add @<username> for <contributions>
```

**\<contributions>**: See the [Emoji Key (Contribution Types Reference)](https://allcontributors.org/docs/en/emoji-key) for a list of valid contribution types.

## Maintainers

- [Vansh Goel](https://github.com/vanshg395/)
- [Alex N'Guessan](https://github.com/marcaureln/)

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://sabikrahat.github.io/"><img src="https://avatars.githubusercontent.com/u/49031412?v=4" width="100px;" alt="Md. Sabik Alam Rahat"/><br /><sub><b>Md. Sabik Alam Rahat</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=sabikrahat" title="Code">💻</a> <a href="https://github.com/vanshg395/intl_phone_field/commits?author=sabikrahat" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://vansh.codes"><img src="https://avatars.githubusercontent.com/u/34906419?v=4?s=100" width="100px;" alt="Vansh Goel"/><br /><sub><b>Vansh Goel</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=vanshg395" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/Kunodayo_oboete"><img src="https://avatars.githubusercontent.com/u/23455702?v=4?s=100" width="100px;" alt="KNO3"/><br /><sub><b>KNO3</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=kno3a87" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.techarge.co.uk"><img src="https://avatars.githubusercontent.com/u/850493?v=4?s=100" width="100px;" alt="Ling Li"/><br /><sub><b>Ling Li</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=lingster" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://linkedin.com/in/anggaraputrapratama"><img src="https://avatars.githubusercontent.com/u/75307272?v=4?s=100" width="100px;" alt="Anggara Putra Pratama"/><br /><sub><b>Anggara Putra Pratama</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=anggaraputrapratama" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://geewax.org"><img src="https://avatars.githubusercontent.com/u/112928?v=4?s=100" width="100px;" alt="JJ Geewax"/><br /><sub><b>JJ Geewax</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=jgeewax" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KevalPrajapati"><img src="https://avatars.githubusercontent.com/u/63007835?v=4?s=100" width="100px;" alt="Keval Prajapati"/><br /><sub><b>Keval Prajapati</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=KevalPrajapati" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/2000calories"><img src="https://avatars.githubusercontent.com/u/25191098?v=4?s=100" width="100px;" alt="hans.huang"/><br /><sub><b>hans.huang</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=2000calories" title="Code">💻</a> <a href="https://github.com/vanshg395/intl_phone_field/commits?author=2000calories" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/The-Redhat"><img src="https://avatars.githubusercontent.com/u/33162310?v=4?s=100" width="100px;" alt="Gregor Weber"/><br /><sub><b>Gregor Weber</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=The-Redhat" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://beacons.ai/hanyi00i"><img src="https://avatars.githubusercontent.com/u/92980326?v=4?s=100" width="100px;" alt="Ooi Han Yi"/><br /><sub><b>Ooi Han Yi</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=hanyi00i" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.jimmyff.co.uk"><img src="https://avatars.githubusercontent.com/u/298850?v=4?s=100" width="100px;" alt="Jimmy Forrester-Fellowes"/><br /><sub><b>Jimmy Forrester-Fellowes</b></sub></a><br /><a href="https://github.com/vanshg395/intl_phone_field/commits?author=jimmyff" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## LICENSE

This project is licensed under the MIT license. See [LICENSE](LICENSE) for more information.

<!-- </details> -->
