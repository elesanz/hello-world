# hello-world
[window, windowRect] = Screen('OpenWindow', 0, 0);
HideCursor;
Screen('TextFont',window, 'Arial');
Screen('TextSize',window, 60);
DrawFormattedText(window,'Hello World!!', 'center', 'center', [120 180 50]);
Screen('Flip', window);
WaitSecs(5);
Screen('CloseAll');
ShowCursor;
