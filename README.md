# batch-transcode
Transcode all FLAC in a directory to LAME-encoded mp3 (V0, V2, 320).

**IMPORTANT**: This deletes the original FLAC files after conversion. This is intentional, as this utility is designed for use as part of a "whatbetter" workflow.

###Synopsis:
	flacbatch [options]

###Installation:
	Save "flacbatch" in user's PATH.
	Ensure it's executable ("chmod +x flacbatch").

###Use:
	Navigate to the directory where your FLAC files are stored.
	Run flacbatch ("flacbatch [options]").

###Options:
* **V0, v0**
	- Output is variable bitrate V0
* **V2, v2**
	- Output is variable bitrate V2
* **320**
	- Output is constant bitrate 320kpbs
