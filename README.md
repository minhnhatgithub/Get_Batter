RunCMD("adb -s 33008dbca2a22489 shell dumpsys battery");
Regex.Match(get, "level: (.*)").Groups[1].ToString();
