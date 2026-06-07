# Pakistan IPTV Guide

This repository generates a public XMLTV EPG guide for Pakistani TV channels using the open-source `iptv-org/epg` project.

## Final URLs

Official Pakistan M3U playlist:

```text
https://iptv-org.github.io/iptv/countries/pk.m3u
```

Custom Pakistan M3U playlist from this repository:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/pakistan.m3u
```

EPG XMLTV guide:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/guide.xml
```

Compressed EPG XMLTV guide:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/guide.xml.gz
```

Replace `YOUR_USERNAME` with your GitHub username.

## Recommended TV Setup

Use either M3U playlist URL:

```text
https://iptv-org.github.io/iptv/countries/pk.m3u
```

or:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/pakistan.m3u
```

Then use this EPG URL:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/guide.xml
```

If your IPTV app supports compressed EPG files, you can use:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/pakistan-iptv-guide/main/guide.xml.gz
```

## Notes

- PTCL Smart TV and Nayatel are not currently supported by upstream `iptv-org/epg`.
- This project only uses public/open sources supported by `iptv-org/epg`.
- The custom `pakistan.m3u` file only uses stream URLs already present in the official `iptv-org` Pakistan playlist.
- GitHub Actions updates `guide.xml` and `guide.xml.gz` every night at 02:00 Pakistan time.
