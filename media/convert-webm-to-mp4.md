# Convert webm to mp4

```
$ ffmpeg -i "<name>.webm" -qscale 0 "<name>.mp4"
```

{% hint style="info" %}
The `qscale 0` directive instructs ffmpeg not to adjust quality of the video during conversion.  And with this conversion I can now properly transfer the videos onto my iPad.
{% endhint %}

### Requirements:

* ffmpeg



