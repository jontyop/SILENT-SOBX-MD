        showAdAttribution: true,
        renderLargerThumbnail: true
    };

    message.quoted = {
        key: {
            fromMe: false,
            participant: "0@s.whatsapp.net",
            remoteJid: "status@broadcast"
        },
        message: {
            contactMessage: {
                displayName: `${message.pushName}`, // Ensure this variable is defined and contains the expected value
                vcard: `BEGIN:VCARD\nVERSION:3.0\nN:XL;${message.client.user.name},;;;\nFN:${message.client.user.name},\nitem1.TEL;waid=${number.split('@')[0]}:${number.split('@')[0]}\nitem1.X-ABLabel:Ponsel\nEND:VCARD`,
                jpegThumbnail: thumbnail
            }
        }
    };

    const text = `0ཻུ۪۪ꦽꦼ̷⸙‹•══════════════♡᭄
│       *「 𝗠𝗬 𝗜𝗡𝗧𝗥𝗢 」*
│ *Name      :* ᴿᴵᴶᵁ_editx
│ *Place       :* ᴬᴸᴵᴾᵁᴿᴰᵁᴬᴿ/ᴮᴬᴺᴳᴸᴼᴿᴱ 
│ *Gender    :*  ᴍᴀʟᴇ
│ *Age          :* 18
│ *Phone      :* wa.me/917364934516
│ *IG ID        :* riju_editx 
│ *SECONDWP      :* wa.me/919332446037 
╰═════ꪶ ཻུ۪۪ꦽꦼ̷⸙ ━ ━ ━ ━ ꪶ ཻུ۪۪ꦽꦼ̷⸙`;

    await message.client.sendMessage(message.chat, { text: text, contextInfo: { externalAdReply: linkPreview } }, { quoted: message.quoted || '' });
});
