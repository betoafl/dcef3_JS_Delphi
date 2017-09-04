object MainForm: TMainForm
  Left = 276
  Top = 194
  Width = 872
  Height = 698
  Caption = 'Chromium Embedded'
  Color = clBtnFace
  TransparentColor = True
  TransparentColorValue = clFuchsia
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'Tahoma'
  Font.Style = []
  Menu = MainMenu
  OldCreateOrder = False
  OnCloseQuery = FormCloseQuery
  OnCreate = FormCreate
  PixelsPerInch = 96
  TextHeight = 13
  object Splitter: TSplitter
    Left = 0
    Top = 430
    Width = 864
    Height = 3
    Cursor = crVSplit
    Align = alBottom
    Visible = False
  end
  object spl2: TSplitter
    Left = 674
    Top = 25
    Width = 5
    Height = 405
    Align = alRight
  end
  object crm: TChromium
    Left = 0
    Top = 25
    Width = 674
    Height = 405
    Align = alClient
    DefaultUrl = 'http://www.google.com'
    TabOrder = 0
    OnProcessMessageReceived = crmProcessMessageReceived
    OnLoadStart = crmLoadStart
    OnLoadEnd = crmLoadEnd
    OnBeforeContextMenu = crmBeforeContextMenu
    OnContextMenuCommand = crmContextMenuCommand
    OnAddressChange = crmAddressChange
    OnTitleChange = crmTitleChange
    OnStatusMessage = crmStatusMessage
    OnConsoleMessage = crmConsoleMessage
    OnBeforeDownload = crmBeforeDownload
    OnDownloadUpdated = crmDownloadUpdated
    OnBeforePopup = crmBeforePopup
    OnBeforeResourceLoad = crmBeforeResourceLoad
    OnCertificateError = crmCertificateError
  end
  object DevTools: TChromiumDevTools
    Left = 0
    Top = 433
    Width = 864
    Height = 200
    Align = alBottom
    Visible = False
  end
  object StatusBar: TStatusBar
    Left = 0
    Top = 633
    Width = 864
    Height = 19
    Panels = <>
    SimplePanel = True
  end
  object Panel1: TPanel
    Left = 0
    Top = 0
    Width = 864
    Height = 25
    Align = alTop
    TabOrder = 2
    DesignSize = (
      864
      25)
    object SpeedButton1: TSpeedButton
      Left = 0
      Top = 0
      Width = 23
      Height = 22
      Action = actPrev
    end
    object SpeedButton2: TSpeedButton
      Left = 24
      Top = 0
      Width = 23
      Height = 22
      Action = actNext
    end
    object SpeedButton3: TSpeedButton
      Left = 48
      Top = 0
      Width = 23
      Height = 22
      Action = actHome
    end
    object SpeedButton4: TSpeedButton
      Left = 72
      Top = 0
      Width = 23
      Height = 22
      Action = actReload
    end
    object SpeedButton5: TSpeedButton
      Left = 841
      Top = 0
      Width = 23
      Height = 22
      Action = actGoTo
      Anchors = [akTop, akRight]
    end
    object edAddress: TEdit
      Left = 95
      Top = 0
      Width = 744
      Height = 21
      Anchors = [akLeft, akTop, akRight]
      TabOrder = 0
      Text = 'http://www.google.com'
      OnKeyPress = edAddressKeyPress
    end
  end
  object pnl1: TPanel
    Left = 679
    Top = 25
    Width = 185
    Height = 405
    Align = alRight
    TabOrder = 4
    object spl1: TSplitter
      Left = 1
      Top = 310
      Width = 183
      Height = 5
      Cursor = crVSplit
      Align = alBottom
    end
    object mmo1: TMemo
      Left = 1
      Top = 1
      Width = 183
      Height = 309
      Align = alClient
      Lines.Strings = (
        'mmo1')
      ScrollBars = ssBoth
      TabOrder = 0
    end
    object mmo2: TMemo
      Left = 1
      Top = 315
      Width = 183
      Height = 89
      Align = alBottom
      Lines.Strings = (
        'mmo2')
      ScrollBars = ssBoth
      TabOrder = 1
    end
    object btn1: TButton
      Left = 104
      Top = 280
      Width = 75
      Height = 25
      Caption = 'Executar JS'
      TabOrder = 2
      OnClick = btn1Click
    end
  end
  object ActionList: TActionList
    Left = 624
    Top = 112
    object actPrev: TAction
      Caption = '<-'
      Enabled = False
      OnExecute = actPrevExecute
      OnUpdate = actPrevUpdate
    end
    object actNext: TAction
      Caption = '->'
      Enabled = False
      OnExecute = actNextExecute
      OnUpdate = actNextUpdate
    end
    object actHome: TAction
      Caption = 'H'
      OnExecute = actHomeExecute
      OnUpdate = actHomeUpdate
    end
    object actReload: TAction
      Caption = 'R'
      OnExecute = actReloadExecute
      OnUpdate = actReloadUpdate
    end
    object actGoTo: TAction
      Caption = '>'
      OnExecute = actGoToExecute
    end
    object actGetSource: TAction
      Caption = 'Get source'
      OnExecute = actGetSourceExecute
    end
    object actGetText: TAction
      Caption = 'Get text'
      OnExecute = actGetTextExecute
    end
    object actZoomIn: TAction
      Caption = 'Zoom in'
      OnExecute = actZoomInExecute
    end
    object actZoomOut: TAction
      Caption = 'Zoom out'
      OnExecute = actZoomOutExecute
    end
    object actZoomReset: TAction
      Caption = 'Zoom reset'
      OnExecute = actZoomResetExecute
    end
    object actExecuteJS: TAction
      Caption = 'Execute JavaScript'
      OnExecute = actExecuteJSExecute
    end
    object actDom: TAction
      Caption = 'Hook DOM'
      OnExecute = actDomExecute
    end
    object actDevTool: TAction
      AutoCheck = True
      Caption = 'Show DevTools'
      OnExecute = actDevToolExecute
    end
    object actDoc: TAction
      Caption = 'Documentation'
      OnExecute = actDocExecute
    end
    object actGroup: TAction
      Caption = 'Google group'
      OnExecute = actGroupExecute
    end
    object actFileScheme: TAction
      Caption = 'File Scheme'
      OnExecute = actFileSchemeExecute
    end
    object actPrint: TAction
      Caption = 'Print'
      OnExecute = actPrintExecute
    end
  end
  object MainMenu: TMainMenu
    Left = 624
    Top = 56
    object File1: TMenuItem
      Caption = '&File'
      object Print1: TMenuItem
        Action = actPrint
      end
      object Exit1: TMenuItem
        Caption = 'Exit'
        ShortCut = 16465
        OnClick = Exit1Click
      end
    end
    object est1: TMenuItem
      Caption = '&Test'
      object mGetsource: TMenuItem
        Action = actGetSource
      end
      object mGetText: TMenuItem
        Action = actGetText
      end
      object ExecuteJavaScript1: TMenuItem
        Action = actExecuteJS
      end
      object Zoomin1: TMenuItem
        Action = actZoomIn
      end
      object Zoomout1: TMenuItem
        Action = actZoomOut
      end
      object Zoomreset1: TMenuItem
        Action = actZoomReset
      end
      object actFileScheme1: TMenuItem
        Action = actFileScheme
      end
      object VisitDOM1: TMenuItem
        Action = actDom
      end
      object DevelopperTools1: TMenuItem
        Action = actDevTool
        AutoCheck = True
        ShortCut = 123
      end
    end
    object Help1: TMenuItem
      Caption = 'Help'
      object Documentation1: TMenuItem
        Action = actDoc
      end
      object Googlegroup1: TMenuItem
        Action = actGroup
      end
    end
  end
  object SaveDialog: TSaveDialog
    Options = [ofOverwritePrompt, ofHideReadOnly, ofEnableSizing]
    Left = 624
    Top = 176
  end
  object tmr1: TTimer
    Enabled = False
    Interval = 1500
    OnTimer = tmr1Timer
    Left = 424
    Top = 336
  end
end
