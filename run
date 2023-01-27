const morseCodes = {
  'a': '.-',
  'b': '-...',
  'c': '-.-.',
  'd': '-..',
  'e': '.',
  'f': '..-.',
  'g': '--.',
  'h': '....',
  'i': '..',
  'j': '.---',
  'k': '-.-',
  'l': '.-..',
  'm': '--',
  'n': '-.',
  'o': '---',
  'p': '.--.',
  'q': '--.-',
  'r': '.-.',
  's': '...',
  't': '-',
  'u': '..-',
  'v': '...-',
  'w': '.--',
  'x': '-..-',
  'y': '-.--',
  'z': '--..'
};

function convertToMorse(str) {
  let result = '';
  for (let i = 0; i < str.length; i++) {
    let char = str[i].toLowerCase();
    if (morseCodes.hasOwnProperty(char)) {
      result += morseCodes[char];
    }
  }
  return result;
}
