## to swap keys " with < 

hidutil property --set '{"UserKeyMapping":[{"HIDKeyboardModifierMappingSrc": 0x700000035,
      "HIDKeyboardModifierMappingDst": 0x700000064
    },
{
      "HIDKeyboardModifierMappingSrc": 0x700000064,
      "HIDKeyboardModifierMappingDst": 0x700000035
    }]}'

## to reset

hidutil property --set '{"UserKeyMapping":[]}'


## next up automation this process

