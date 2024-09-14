# text-recognition-with-copilot
Repo for the final project of DIO Microsoft Copilot AI bootcamp

The images in the "inputs" directory where feed one by one to [Microsoft Copilot via web browser](https://copilot.microsoft.com/), with the following prompt:
"Tell me what's written on the image"

The results where copied and pasted on the directory "outputs", each one in the correspondent file.

## Some observations:
- Big letters with contrasting colors are easily read by Copilot
- Copilot ignores some figures as texts, as the 3D "+" on image2 text. Where we read "Treine +", Copilot only reads "Treine"
- It not only shows the text on the image, but tends to understand it's context, even trying to make a conversation out of it
- Copilot also recognizes objects on the image and mentions them, even when not being explicitly asked to.
- It may overlook smallsized and secondary texts, like the timestamp on image3.jpeg
- It includes emojis on the answer 😁