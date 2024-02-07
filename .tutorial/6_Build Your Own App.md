# Step 6: Build your own app
## Project Start
Now, head over to `Tab3.tsx` to start building. Use components like `CardWrapper.tsx` for neat info cards or `CarouselWrapper.tsx` for a slideshow.
## Customization Tips
Remember, you can change the text, colors, and even sizes of most components. Make your app truly yours.
## Design Creativity
Feel free to experiment. The best apps come from trying new things. What if your app had a theme, like underwater or outer space?

## Reset

If you need to reset, you can copy and paste the following into `Tab3.tsx`

```
import React from 'react';
import {Group, Paper, Stack, Title, useMantineTheme} from '@mantine/core';
import GiphyWrapper from '../components/GiphyWrapper';
import ImageWrapper from '../components/ImageWrapper';
import CardWrapper from '../components/CardWrapper';
import InstagramWrapper from '../components/InstagramWrapper';
import TikTokWrapper from '../components/TikTokWrapper';
import YouTubeWrapper from '../components/YouTubeWrapper';
import ButtonWrapper from '../components/ButtonWrapper';
import AccordianWrapper from '../components/AccordianWrapper';
import CalenderWrapper from '../components/CalenderWrapper';
import CarouselWrapper from '../components/CarouselWrapper';

const Tab3 = () => {
  const theme = useMantineTheme();
  return (
    <Stack bg={theme.colors.gray[0]} align="center">
      <Title p={30}>Start making your cool webpage here! 🚀️</Title>
    </Stack>
  );
};

export default Tab3;
```