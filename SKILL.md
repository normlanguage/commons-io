# commons.io Skill

Use this skill to work with Norm module `commons.io` version 3. Use only declarations listed below.

## `commons.io`

Source: `FileUtils.norm`

### `FileUtils`

```norm
class FileUtils
```

#### `FileUtils`

```norm
FileUtils(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `fileUtilsCleanDirectory`

```norm
Void fileUtilsCleanDirectory(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsContentEquals`

```norm
Boolean fileUtilsContentEquals(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Boolean`

### `fileUtilsCopyDirectoryToDirectory`

```norm
Void fileUtilsCopyDirectoryToDirectory(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Void`

### `fileUtilsCopyFileToDirectory`

```norm
Void fileUtilsCopyFileToDirectory(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Void`

### `fileUtilsCopyFileToDirectory`

```norm
Void fileUtilsCopyFileToDirectory(File? arg0, File? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsCopyToDirectory`

```norm
Void fileUtilsCopyToDirectory(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Void`

### `fileUtilsCopyToDirectory`

```norm
Void fileUtilsCopyToDirectory(Function<Iterator<File>?()>? arg0, File? arg1)
```

Parameters:

- `arg0`: `Function<Iterator<File>?()>?`
- `arg1`: `File?`

Returns: `Void`

### `fileUtilsCreateParentDirectories`

```norm
File? fileUtilsCreateParentDirectories(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `File?`

### `fileUtilsDelete`

```norm
File? fileUtilsDelete(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `File?`

### `fileUtilsDeleteDirectory`

```norm
Void fileUtilsDeleteDirectory(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsDeleteQuietly`

```norm
Boolean fileUtilsDeleteQuietly(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Boolean`

### `fileUtilsDirectoryContains`

```norm
Boolean fileUtilsDirectoryContains(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Boolean`

### `fileUtilsForceDelete`

```norm
Void fileUtilsForceDelete(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsForceMkdir`

```norm
Void fileUtilsForceMkdir(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsForceMkdirParent`

```norm
Void fileUtilsForceMkdirParent(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsGetTempDirectory`

```norm
File? fileUtilsGetTempDirectory()
```

Returns: `File?`

### `fileUtilsGetTempDirectoryPath`

```norm
String? fileUtilsGetTempDirectoryPath()
```

Returns: `String?`

### `fileUtilsGetUserDirectory`

```norm
File? fileUtilsGetUserDirectory()
```

Returns: `File?`

### `fileUtilsGetUserDirectoryPath`

```norm
String? fileUtilsGetUserDirectoryPath()
```

Returns: `String?`

### `fileUtilsIsEmptyDirectory`

```norm
Boolean fileUtilsIsEmptyDirectory(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Boolean`

### `fileUtilsIsSymlink`

```norm
Boolean fileUtilsIsSymlink(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Boolean`

### `fileUtilsMoveDirectory`

```norm
Void fileUtilsMoveDirectory(File? arg0, File? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`

Returns: `Void`

### `fileUtilsMoveDirectoryToDirectory`

```norm
Void fileUtilsMoveDirectoryToDirectory(File? arg0, File? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsMoveFileToDirectory`

```norm
Void fileUtilsMoveFileToDirectory(File? arg0, File? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsMoveToDirectory`

```norm
Void fileUtilsMoveToDirectory(File? arg0, File? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `File?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsReadFileToByteArray`

```norm
JavaByteArray? fileUtilsReadFileToByteArray(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `JavaByteArray?`

### `fileUtilsReadFileToString`

```norm
String? fileUtilsReadFileToString(File? arg0, String? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`

Returns: `String?`

### `fileUtilsReadFileToString`

```norm
String? fileUtilsReadFileToString(File? arg0, Charset? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Charset?`

Returns: `String?`

### `fileUtilsReadLines`

```norm
JavaList<String>? fileUtilsReadLines(File? arg0, String? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`

Returns: `JavaList<String>?`

### `fileUtilsReadLines`

```norm
JavaList<String>? fileUtilsReadLines(File? arg0, Charset? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Charset?`

Returns: `JavaList<String>?`

### `fileUtilsSizeOf`

```norm
Long fileUtilsSizeOf(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Long`

### `fileUtilsSizeOfDirectory`

```norm
Long fileUtilsSizeOfDirectory(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Long`

### `fileUtilsTouch`

```norm
Void fileUtilsTouch(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Void`

### `fileUtilsWrite`

```norm
Void fileUtilsWrite(File? arg0, CharSequence? arg1, String? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `CharSequence?`
- `arg2`: `String?`

Returns: `Void`

### `fileUtilsWrite`

```norm
Void fileUtilsWrite(File? arg0, CharSequence? arg1, String? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `CharSequence?`
- `arg2`: `String?`
- `arg3`: `Boolean`

Returns: `Void`

### `fileUtilsWrite`

```norm
Void fileUtilsWrite(File? arg0, CharSequence? arg1, Charset? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `CharSequence?`
- `arg2`: `Charset?`

Returns: `Void`

### `fileUtilsWrite`

```norm
Void fileUtilsWrite(File? arg0, CharSequence? arg1, Charset? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `CharSequence?`
- `arg2`: `Charset?`
- `arg3`: `Boolean`

Returns: `Void`

### `fileUtilsWriteByteArrayToFile`

```norm
Void fileUtilsWriteByteArrayToFile(File? arg0, JavaByteArray? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `JavaByteArray?`

Returns: `Void`

### `fileUtilsWriteByteArrayToFile`

```norm
Void fileUtilsWriteByteArrayToFile(File? arg0, JavaByteArray? arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `JavaByteArray?`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `Void`

### `fileUtilsWriteByteArrayToFile`

```norm
Void fileUtilsWriteByteArrayToFile(File? arg0, JavaByteArray? arg1, Integer arg2, Integer arg3, Boolean arg4)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `JavaByteArray?`
- `arg2`: `Integer`
- `arg3`: `Integer`
- `arg4`: `Boolean`

Returns: `Void`

### `fileUtilsWriteByteArrayToFile`

```norm
Void fileUtilsWriteByteArrayToFile(File? arg0, JavaByteArray? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `JavaByteArray?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, String? arg1, Collection<?>? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Collection<?>?`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, String? arg1, Collection<?>? arg2, String? arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Collection<?>?`
- `arg3`: `String?`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, String? arg1, Collection<?>? arg2, String? arg3, Boolean arg4)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Collection<?>?`
- `arg3`: `String?`
- `arg4`: `Boolean`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, String? arg1, Collection<?>? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Collection<?>?`
- `arg3`: `Boolean`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, Collection<?>? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Collection<?>?`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, Collection<?>? arg1, String? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Collection<?>?`
- `arg2`: `String?`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, Collection<?>? arg1, String? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Collection<?>?`
- `arg2`: `String?`
- `arg3`: `Boolean`

Returns: `Void`

### `fileUtilsWriteLines`

```norm
Void fileUtilsWriteLines(File? arg0, Collection<?>? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `Collection<?>?`
- `arg2`: `Boolean`

Returns: `Void`

### `fileUtilsWriteStringToFile`

```norm
Void fileUtilsWriteStringToFile(File? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `Void`

### `fileUtilsWriteStringToFile`

```norm
Void fileUtilsWriteStringToFile(File? arg0, String? arg1, String? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `String?`
- `arg3`: `Boolean`

Returns: `Void`

### `fileUtilsWriteStringToFile`

```norm
Void fileUtilsWriteStringToFile(File? arg0, String? arg1, Charset? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Charset?`

Returns: `Void`

### `fileUtilsWriteStringToFile`

```norm
Void fileUtilsWriteStringToFile(File? arg0, String? arg1, Charset? arg2, Boolean arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `Charset?`
- `arg3`: `Boolean`

Returns: `Void`

## `commons.io`

Source: `FilenameUtils.norm`

### `FilenameUtils`

```norm
class FilenameUtils
```

#### `FilenameUtils`

```norm
FilenameUtils(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `filenameUtilsConcat`

```norm
String? filenameUtilsConcat(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `filenameUtilsDirectoryContains`

```norm
Boolean filenameUtilsDirectoryContains(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsEquals`

```norm
Boolean filenameUtilsEquals(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsEquals`

```norm
Boolean filenameUtilsEquals(String? arg0, String? arg1, Boolean arg2, IOCase? arg3)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Boolean`
- `arg3`: `IOCase?`

Returns: `Boolean`

### `filenameUtilsEqualsNormalized`

```norm
Boolean filenameUtilsEqualsNormalized(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsEqualsOnSystem`

```norm
Boolean filenameUtilsEqualsOnSystem(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsGetBaseName`

```norm
String? filenameUtilsGetBaseName(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsGetExtension`

```norm
String? filenameUtilsGetExtension(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsGetFullPath`

```norm
String? filenameUtilsGetFullPath(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsGetName`

```norm
String? filenameUtilsGetName(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsGetPath`

```norm
String? filenameUtilsGetPath(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsGetPrefix`

```norm
String? filenameUtilsGetPrefix(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsIndexOfExtension`

```norm
Integer filenameUtilsIndexOfExtension(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Integer`

### `filenameUtilsIndexOfLastSeparator`

```norm
Integer filenameUtilsIndexOfLastSeparator(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Integer`

### `filenameUtilsIsExtension`

```norm
Boolean filenameUtilsIsExtension(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsIsExtension`

```norm
Boolean filenameUtilsIsExtension(String? arg0, Collection<String>? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Collection<String>?`

Returns: `Boolean`

### `filenameUtilsIsExtension`

```norm
Boolean filenameUtilsIsExtension(String? arg0, JavaStringArray? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `JavaStringArray?`

Returns: `Boolean`

### `filenameUtilsNormalize`

```norm
String? filenameUtilsNormalize(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsNormalize`

```norm
String? filenameUtilsNormalize(String? arg0, Boolean arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Boolean`

Returns: `String?`

### `filenameUtilsRemoveExtension`

```norm
String? filenameUtilsRemoveExtension(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsSeparatorsToSystem`

```norm
String? filenameUtilsSeparatorsToSystem(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsSeparatorsToUnix`

```norm
String? filenameUtilsSeparatorsToUnix(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsSeparatorsToWindows`

```norm
String? filenameUtilsSeparatorsToWindows(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `filenameUtilsWildcardMatch`

```norm
Boolean filenameUtilsWildcardMatch(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Boolean`

### `filenameUtilsWildcardMatch`

```norm
Boolean filenameUtilsWildcardMatch(String? arg0, String? arg1, IOCase? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `IOCase?`

Returns: `Boolean`

## `commons.io`

Source: `IOCase.norm`

### `IOCase`

```norm
enum IOCase
```

#### `INSENSITIVE`

```norm
INSENSITIVE
```

#### `SENSITIVE`

```norm
SENSITIVE
```

#### `SYSTEM`

```norm
SYSTEM
```

## `commons.io`

Source: `IOUtils.norm`

### `IOUtils`

```norm
class IOUtils
```

#### `IOUtils`

```norm
IOUtils(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `ioUtilsToBufferedInputStream`

```norm
InputStream? ioUtilsToBufferedInputStream(InputStream? arg0)
```

Parameters:

- `arg0`: `InputStream?`

Returns: `InputStream?`

### `ioUtilsToBufferedInputStream`

```norm
InputStream? ioUtilsToBufferedInputStream(InputStream? arg0, Integer arg1)
```

Parameters:

- `arg0`: `InputStream?`
- `arg1`: `Integer`

Returns: `InputStream?`

### `ioUtilsToInputStream`

```norm
InputStream? ioUtilsToInputStream(CharSequence? arg0, String? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `String?`

Returns: `InputStream?`

### `ioUtilsToInputStream`

```norm
InputStream? ioUtilsToInputStream(CharSequence? arg0, Charset? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Charset?`

Returns: `InputStream?`

### `ioUtilsToInputStream`

```norm
InputStream? ioUtilsToInputStream(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `InputStream?`

### `ioUtilsToInputStream`

```norm
InputStream? ioUtilsToInputStream(String? arg0, Charset? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Charset?`

Returns: `InputStream?`

## `commons.io`

Source: `JavaArrays.norm`

### `JavaByteArray`

```norm
class JavaByteArray
```

#### `JavaByteArray`

```norm
JavaByteArray(JavaByteArrayBindingToken token)
```

Parameters:

- `token`: `JavaByteArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaByteArrayNew`

```norm
JavaByteArray javaByteArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaByteArray`

### `JavaStringArray`

```norm
class JavaStringArray
```

#### `JavaStringArray`

```norm
JavaStringArray(JavaStringArrayBindingToken token)
```

Parameters:

- `token`: `JavaStringArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
String? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `String?`

#### `set`

```norm
Void set(Integer index, String? value)
```

Parameters:

- `index`: `Integer`
- `value`: `String?`

Returns: `Void`

### `javaStringArrayNew`

```norm
JavaStringArray javaStringArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaStringArray`

